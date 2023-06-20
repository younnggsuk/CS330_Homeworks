# CS330 Homeworks
This repository contains my solutions to the homeworks of the [CS330: Multi-Task and Meta-Learning, Fall 2022](https://cs330.stanford.edu/) course at Stanford University.

## Requirements
All homework assignments are implemented in Python 3.9.  
To install the required packages, run the following command in each homework directory.

#### Using pip
```bash
$ pip install -r requirements.txt
```

#### Using pipenv
```bash
$ pipenv install
```

## Homeworks

### [2. Prototypical Networks and Model-Agnostic Meta-Learning](hw2/)

#### Change directory to homework 2
```bash
$ cd hw2
```

#### Download the Omniglot dataset
```bash
$ gdown https://drive.google.com/uc\?id\=1iaSFXIYC3AB8q9K_M-oVMa4pmB7yKMtI
$ unzip omniglot_resized.zip
```

#### Prototypical Networks
```bash
$ python protonet.py
```

#### Model-Agnostic Meta-Learning
```bash
$ python maml.py
```
