# BERTopic Topic Modeling on Text from Project Gutenberg

This project demonstrates how to apply topic modeling using **BERTopic** on a text dataset from Project Gutenberg. The text is processed, cleaned, tokenized, and normalized before applying BERTopic for topic modeling and visualization.

## Table of Contents
1. [Introduction](#introduction)
2. [Prerequisites](#prerequisites)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Visualization](#visualization)
6. [License](#license)

## Introduction
This project downloads the full text of *The Adventures of Sherlock Holmes* from Project Gutenberg, processes the text by cleaning, tokenizing, and normalizing it, then applies **BERTopic** for topic modeling. The topics and their distributions are visualized for better interpretation.

## Prerequisites
Make sure you have Python 3.6+ installed along with the following libraries:

- **nltk**: Used for text preprocessing (tokenization, stopword removal, lemmatization)
- **requests**: To download the text from Project Gutenberg
- **BERTopic**: For topic modeling
- **scikit-learn**: For vectorization
- **sentence-transformers**: To generate sentence embeddings

## Installation

1. **Clone this repository:**

```bash
git clone https://github.com/yourusername/bertopic-project.git
cd bertopic-project
```
2. **Install required libraries:**

```bash
pip install -r requirements.txt
```
3. **Alternatively, you can install the necessary libraries manually using:**

```bash
pip install nltk requests bertopic scikit-learn sentence-transformers
```
## Usage

### 1. Download the text:
The project downloads *The Adventures of Sherlock Holmes* from Project Gutenberg.

### 2. Preprocess the text:
The text is cleaned, tokenized, stopwords are removed, and lemmatization is performed.

### 3. Apply BERTopic:
The text is split into chunks, and BERTopic is applied to extract topics.

### 4. Visualize the topics:
Visualizations are generated to interpret the topics and their distributions.

## Running the Script

1. Clone the repository and install the necessary dependencies as shown above.

2. Run the script to download the text, preprocess it, apply BERTopic, and visualize the results.

```bash
python topic_modeling.py
```
## Example of visualization:

```bash
topic_model.visualize_topics().show()  # Displays the topic visualization
topic_model.visualize_distribution(probs[0]).show()  # Displays topic distribution for the first document
```
