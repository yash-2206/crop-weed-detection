# Crop and Weed Detection System

## Project Overview
This project aims to develop a system that selectively sprays pesticides on weeds, minimizing pesticide waste and reducing contamination of crops. The system uses a deep learning model to detect and differentiate between crops and weeds in agricultural images.

## Dataset
The dataset contains 1300 images of sesame crops and various types of weeds, each labeled in YOLO format. The images are 512x512 pixels in size.

**Dataset Link:** [Google Drive Link](https://drive.google.com/file/d/1MNdDKYB0x0PEW7P71bE1Jx_uLllvORA0/view?usp=sharing)
## Project Structure
crop-weed-detection/
├── data/
│ ├── raw/
│ ├── processed/
├── notebooks/
├── src/
│ ├── data_preprocessing.py
│ ├── data_augmentation.py
│ ├── model_training.py
│ ├── inference.py
├── README.md
├── requirements.txt
├── .gitignore