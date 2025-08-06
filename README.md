# Hand Gesture Recognition using CNN

## Project Overview
This project involves training a simple Convolutional Neural Network (CNN) to recognize hand gestures representing numbers from 1 to 3, as well as thumb direction gestures.  
The dataset consists of 13 images per class, where each class corresponds to a specific hand gesture.

## Dataset
- Classes:  
  - Numbers 1, 2, and 3 represented by fingers  
  - Thumb directions (e.g., up, down, left, right) with 24 images each  
- Total images: 24 images per class  
- Images are preprocessed and labeled for training

## Model
- A simple CNN architecture was used for classification.  
- Input: images of hand gestures  
- Output: predicted gesture class  

## Training & Evaluation
- The model was trained on the dataset with appropriate train-test split.  
- Accuracy and loss metrics were recorded during training.  
- Prediction accuracy graphs have been generated to visualize model performance over epochs.

## Results
- Accuracy graphs demonstrate how well the CNN learned to recognize different hand gestures.  
- The model achieved promising accuracy despite the small dataset size, showing feasibility for simple gesture recognition tasks.

## Usage
- The trained model can be used to predict hand gestures from new images.  
- This project can be extended by increasing dataset size or adding more gesture classes for improved performance.

## Requirements
- Python 3.x  
- TensorFlow / Keras  
- OpenCV (optional for image preprocessing)  
- Matplotlib (for plotting accuracy graphs)

## How to Run
1. Prepare dataset folder structure with images labeled per class. (create your own or download in here https://drive.google.com/drive/folders/1dUkKfemDIJxOXu1V-1t7l6EWQjAEYt-M?usp=share_link)
2. Run the training script to train the CNN model.  
3. Use the evaluation script to generate accuracy and loss graphs.  
4. Test the model with new hand gesture images for prediction.
