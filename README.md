# Pokémon Legendary Classification
![Pokemon Image](./res/pokemon.png)


## Overview
Welcome to the Pokémon Legendary Classification project! In this repository, we have developed a machine-learning model that predicts whether a Pokémon is legendary or not based on various features. This project uses a dataset that contains information about 721 Pokémon, including their attributes such as type, stats, and more.

## About the Dataset
The dataset used in this project includes the following attributes for each Pokémon:

* ID: Unique identification number for each Pokémon.
* Name: The name of each Pokémon.
* Type 1: The primary type of the Pokémon, determines its weaknesses and resistance to attacks.
* Type 2: Some Pokémon have a secondary type in addition to their primary type.
* Total: The sum of all stats that come after this attribute, providing a general guide to a Pokémon's overall strength.
* HP: Hit points, or health, indicating how much damage a Pokémon can withstand before fainting.
* Attack: The base modifier for normal attacks (e.g., Scratch, Punch).
* Defense: The base damage resistance against normal attacks.
* SP Atk: Special attack, the base modifier for special attacks (e.g., fire blast, bubble beam).
* SP Def: The base damage resistance against special attacks.
* Speed: Determines which Pokémon attacks first in each round.

## Purpose
This dataset has proven to be valuable in teaching statistics and, interestingly, can be used as an engaging introduction to machine learning. 
It focuses on attributes used in the Pokémon games (not trading cards or Pokémon Go) to calculate damage during battles.

## Machine Learning Model
### Data Preprocessing
Before building our machine learning model, we performed several data preprocessing steps, including:

* Data cleaning: Handling missing values and ensuring data consistency.
* Data splitting: Dividing the dataset into training and testing sets.
* Feature scaling: Scaling the features to ensure uniformity and prevent certain attributes from dominating the model.

### Model Architecture
I implemented a Feed Forward Neural Network for classification. The model takes the Pokémon attributes as input and predicts whether a Pokémon is legendary or not as output.
I trained the model using appropriate training techniques.

### Dealing with Imbalanced Classes
The dataset had an imbalance in the legendary and non-legendary classes. To address this issue, I used the AUC (Area Under the Curve) metric to evaluate model performance. 
AUC is a robust metric for imbalanced datasets, providing a better understanding of classification performance.

## Credits
* Dataset Source: https://www.kaggle.com/datasets/abcsds/pokemon)https://www.kaggle.com/datasets/abcsds/pokemon
* Dataset Author: Myles O'Neill
