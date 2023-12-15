# Milky Shaky LAB - web scraping

### install pyenv.
	$ curl -L https://github.com/pyenv/pyenv-installer/raw/master/bin/pyenv-installer | bash
#### in the .zshrc add in the end of the file.
	export PYENV_ROOT="$HOME/.pyenv"
	[[ -d $PYENV_ROOT/bin ]] && export PATH="$PYENV_ROOT/bin:$PATH"
	eval "$(pyenv init -)"
### update pyenv
	$ pyenv update
### install version python
	$ pyenv install 3.12.1
### create virtual env
	$ ~/.pyenv/versions/3.12.1/bin/python3.12 -m venv ~/projects/milkyshakylab

	$ cd ~/projects/milkyshakylab
	$ source bin/activate
	$ pip install --upgrade pip
	$ pip install scrapy
	$ deactivate
### clone repository
	$ cd ~/projects/milkyshakylab
	$ git clone git@github.com:willtrigo/milky_shaky_lab_web_scraping.git
