# APShoulder

## Directory description
- APShoulder : Contains APShoulder executable file
- DeepLearningModel: Contains APShoulder learning model source files

## Install Anaconda to set up Python

## Create a development environment and folder in Anaconda Prompt
- conda create -n Shoulder_env python=3.8

## Access the development environment
- conda activate Shoulder_env

## Install Pytorch, a machine learning library
- Enter into Anaconda Prompt
  - conda install pytorch==1.5.0 torchvision==0.6.0 cudatoolkit=10.1
  - (It differs depending on the installed version of Cuda. Check the Pytorch Version according to the Cuda version: https://pytorch.org/)

## Install library for learning
- conda install git pip
- pip install git+https://github.com/davidiommi/MONAI_0_7_0.git
- conda pip install simpleITK==2.1.0
- conda pip install torchsummaryX
- conda pip install nibabel
- conda pip install pillow
- conda pip install tensorboard
- conda pip install gdown
- conda pip install pytorch-ignite==0.4.4
- conda pip install itk
- conda pip install tqdm
- conda pip install lmdb
- conda pip install psutil
- conda pip install pandas
- conda pip install einops
- conda pip install scikit-image

## Copy all files in DeepLearningModel to APShoulder

## Copy \anaconda3\envs\Shoulder_env to APShoulder

## Install QT 5.15.0

## Install VTK 8.0.0 library

## Install DCMTK 3.6.0 library

## Run the APShoulder.exe file in the APShoulder directory
