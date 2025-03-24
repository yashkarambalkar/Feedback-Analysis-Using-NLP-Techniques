# Feedback Analysis Using NLP Techniques

## Overview
This project focuses on analyzing customer feedback using Natural Language Processing (NLP) techniques. By utilizing the Hugging Face API for sentiment analysis, it provides insights into customer sentiment from Amazon Echo’s Feedback Database, sourced from Kaggle.

## Features
- **Sentiment Analysis:** Analyze short text feedback to classify sentiments (positive, negative, or neutral).
- **Data Pre-processing:** Clean and tokenize feedback data for efficient analysis.
- **Visualization:** Generate insightful reports using Matplotlib's `pyplot`.
- **API Integration:** Implement sentiment analysis using Hugging Face API.
- **Deployment:** Containerized and deployed the project using Docker on Azure.

## Tech Stack
- **Programming Language:** Python
- **Libraries:** Hugging Face Transformers, Pandas, NumPy, Matplotlib
- **APIs:** Hugging Face API
- **Containerization:** Docker
- **Cloud Platform:** Microsoft Azure

## Data Source
- The feedback data used in this project is sourced from [Kaggle](https://www.kaggle.com/) and contains customer reviews for Amazon Echo.

## Installation
Step 1: Clone the repository
```
git clone https://github.com/yashkarambalkar/fba.git
```

Step 2: Open the cloned repository and create a conda environment. Activate the new environment
```
conda create -n yashfeedbackanalysis python=3.10
```
```
conda activate yashfeedbackanalysis
```

Step 3: Install the requirements file
```
pip install -r requirements.txt
```
## Docker Deployment
1. Build the Docker image:
    ```bash
    docker build -t feedback-analysis-nlp .
    ```
2. Run the Docker container:
    ```bash
    docker run -p 5000:5000 feedback-analysis-nlp
    ```
3. Access the application at `http://localhost:5000`

## Results
- Sentiment analysis results are visualized using various plots for stakeholder presentations.
- Actionable insights from customer feedback were derived to inform product improvements.

## Conclusion
This project showcases the effective use of NLP and sentiment analysis to gain meaningful insights from customer feedback. Containerizing and deploying on Azure further demonstrates proficiency in cloud-based deployment.

---

*This project was developed as part of a hands-on learning experience in NLP, data engineering, and cloud deployment.*
