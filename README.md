# Face Emotion Recognition using Machine Learning (Python)

This repository contains code for a Face Emotion Recognition model built using Machine Learning in Python. The model has achieved an accuracy of 62% on the provided dataset.

## Getting Started

### Prerequisites
- Python (3.x recommended)
- Conda (for managing environments)

### Installation

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/wxjxhxt/Face-Emotion-Recognition-using-Machine-Learning-Python.git
    ```

2. Navigate into the project directory:

    ```bash
    cd Face-Emotion-Recognition-using-Machine-Learning-Python
    ```

3. Create a Conda environment using the provided `requirements.txt` file:

    ```bash
    conda create --name emotionrecog --file requirements.txt
    ```

4. Activate the Conda environment:

    ```bash
    conda activate emotionrecog
    ```

### Usage

1. Download the pre-trained model from [Google Drive](https://drive.google.com/drive/folders/1iTQyifa4s6HMipi6FCzjJmOzminFGBHK?usp=sharing) and place it in the root folder of the repository.

2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/jonathanoheix/face-expression-recognition-dataset) and extract it.

3. Organize the dataset folders as follows:

    ```
    Face-Emotion-Recognition-using-Machine-Learning-Python/
        images/
            train/
                    ...
             
                    ...
            test/
                    ...
   ```
**Note:** Rename the 'validation' folder to 'test' and delete any duplicate folders in the dataset. 

4. Run Jupyter Notebook to preprocess the data, train the model, and evaluate its performance:

    ```bash
    jupyter notebook
    ```

5. Open and run the Jupyter Notebook cells (`trainmodel.ipynb`) to preprocess the data, train the model, and evaluate its performance.

6. Run the `realtimedetection.py` script to perform real-time face emotion detection using the trained model:

    ```bash
    python realtimedetection.py
    ```

## Notes

- Make sure to activate your Conda environment (`conda activate emotionrecog`) before running any Python scripts or Jupyter Notebook cells.
- Pay attention to the dataset folder structure and remove any duplicate folders to avoid errors during preprocessing.
