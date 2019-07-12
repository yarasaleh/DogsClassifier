# DogsClassifier
identify which pet images are of dogs and which pet images aren't of dogs.

## Important Notes
For this image classification you will be using an image classification application using a deep learning model called a convolutional neural network (often abbreviated as CNN). CNNs work particularly well for detecting features in images like colors, textures, and edges then using these features to identify objects in the images. You'll use a CNN that has already learned the features from a giant dataset of 1.2 million images called ImageNet. There are different types of CNNs that have different structures (architectures) .You choose whatever works better with the images you're testing .

## Running the program 
#### Step One 
run the following   
`#  Code from run_models_batch.sh 
python check_images.py --dir pet_images/ --arch resnet  --dogfile dognames.txt
     > resnet_pet-images.txt
python check_images.py --dir pet_images/ --arch alexnet  --dogfile dognames.txt  
     > alexnet_pet-images.txt
python check_images.py --dir pet_images/ --arch vgg  --dogfile dognames.txt 
     > vgg_pet-images.txt`
#### Step Two 
To run file run_models_batch.sh in the workspace, open a terminal window (in Unix/Linux/OSX/Lab Workspace) and type the following:
`sh run_models_batch.sh`
If you want to batch process the program on a Windows computer you will need to follow the instructions found [here](https://github.com/udacity/AIPND/blob/master/notes/lab_intro-to-python-lab.md#running-batch-files-on-windows-os-locally).
#### Step Three
To run file run_models_batch_uploaded.sh in the workspace, open a terminal window within the Project Workspace - Uploaded Images and type the following, then hit enter:
`sh run_models_batch_uploaded.sh`


