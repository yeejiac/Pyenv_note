### Pyenv Note

- Install windows pyenv
```
$ pip install pyenv-win

set envrionment variable
```

- Install python version
```
$ pyenv install <version>
```

- Check installed python version
```
$ pyenv versions
```

- Run installed python environment
```
$ pyenv local <version>
```

- Check which python/pip is using
```
$ pyenv which python
$ pyenv which pip
```

- Switch back to system python
```
$ pyenv local --unset
```

### Create virtual environment
```
$ pyenv virtualenv <python_version> <environment_name>
```

- Start virtual environment
```
pyenv local <environment_name>
```
