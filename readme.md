# Python Header Examiner

This is a simple script to exam all the import lib of a python project.

## Usage

`python3 exam.py YOUR_PROJECT_PATH YOUR_RESULT_OUTPUT_PATH`

Plz use abs path when you run the scripts.

## Example
*test1.py:*
```
import torch as tf
import math
from torch import nn
import pandas
```
`python3 exam.py ~/test1.py ~/results.txt`

*results.txt:*
```
---------------------------
Lib: torch
Api:
	nn
---------------------------
Lib: math
---------------------------
Lib: pandas
```