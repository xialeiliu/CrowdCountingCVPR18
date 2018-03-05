# The demo for Crowd counting!

## Code and pre-trained models are coming soon.

## Requirements
1. Requirements for ```caffe ``` and  ```pycaffe ``` (see: [Caffe installation instructions](http://caffe.berkeleyvision.org/installation.html)). 
Caffe must be built with support for Python layers!

```
# In your Makefile.config, make sure to have this line uncommented
WITH_PYTHON_LAYER := 1
```
2. Requirements for GPU (Titan X (~11G of memory) is needed to train VGG).

## Pre-trained ImageNet VGG-16 model
Download the pre-trained [VGG-16](https://gist.github.com/ksimonyan/211839e770f7b538e2d8#file-readme-md) ImageNet model and put it in the folder [models](../models).

# Usage
## Training
```
./experiments/train_shanghai.sh
```
## Testing
```
./eval/shanghai_eval.sh
```
