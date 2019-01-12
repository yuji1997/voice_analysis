# voice_analysis in Python
This is a introduction to voice analysis in Python libraries, "pywirld" and "pyreaper".
My development environment is macOS Mojave, version 10.14.2, Python3.7.1 and use pyenv.

**warning!**
Anaconda is not matched for pyworld.
Use .pyenv/shims/python3 or usr/bin/env python3.

## Download
mac OS:

`curl -O https://github.com/yuji1997/voice_analysis`

or

`git clone https://github.com/yuji1997/voice_analysis`

Linux:

`wget https://github.com/yuji1997/voice_analysis`

## directory
```shell
.
├── data
│   └── sample.wav
└── src
    └── voice_analysis.ipynb
```

## Install pyworld

```shell
$ pip install scipy
$ pip install pyworld
```

## Install pyreaper
```shell
$ git clone https://github.com/r9y9/pyreaper
$ cd pyreaper
$ git submodule update --init --recursive
$ python setup.py develop

$ pip install pysptk
```
