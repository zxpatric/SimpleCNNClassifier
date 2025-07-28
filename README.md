# Simple CNN Classifier
This is a very simple repo for explaining basic concepts about 
Convolutional Neural Networks (CNNs) to beginners.
The example exploits the PyTorch library (https://pytorch.org/) 
for performing a basic binary classification task on the Kaggle
Dogs vs. Cats dataset (https://www.kaggle.com/c/dogs-vs-cats/data). or Microsoft clone of Dogs vs. Cats dataset (https://www.microsoft.com/en-us/download/details.aspx?id=54765)

## Preparing the dataset
Consider to Use the script ``prepare_dataset.py`` in order to split train samples into two folders. 
   The data format shall be like below:

   * ./resources/cat-and-dog/training_set/cats/*.jpg
   * ./resources/cat-and-dog/training_set/dogs/*.jpg
   * ./resources/cat-and-dog/test_set/cats/*.jpg
   * ./resources/cat-and-dog/test_set/dogs/*.jpg   

  
## Training
Use the script ``train.py`` in order to train a CNN for this purpose. The trained result model will be stored under ./logs

## Validation
Use the script ``eval.py`` in order to evaluate the CNN performance on this task. The trained result model will be loaded under ./logs


## Training and evaluating in different model
Cat_vs_Dog_with_PyTorch.ipynb