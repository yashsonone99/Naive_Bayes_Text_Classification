# Naive_Bayes_Text_Classification
“A Natural Language Processing (NLP) project using Naive Bayes for text classification and sentiment analysis of blog posts combining TF-IDF vectorization, NLTK preprocessing, and TextBlob insights.”
# 🧾 Naive Bayes Text Classification & Sentiment Analysis

> “An NLP project applying Naive Bayes for multi-class blog categorization and sentiment detection using TF-IDF, NLTK, and TextBlob.”

---

## 💡 Project Overview  
This project focuses on **text classification and sentiment analysis** using the **Naive Bayes algorithm**.  
It processes a collection of blog posts, cleans and tokenizes text using **NLTK**, converts it into numerical features using **TF-IDF**, and classifies content into categories.  
In addition, it applies **sentiment polarity analysis** with **TextBlob** to uncover emotional tone within each blog post.

---

## 🎯 Objectives  
- Load and explore the blog dataset  
- Perform **text cleaning, lemmatization, and stopword removal**  
- Extract numerical features using **TF-IDF Vectorizer**  
- Train a **Multinomial Naive Bayes classifier**  
- Evaluate performance using classification metrics and confusion matrix  
- Perform **sentiment analysis** using TextBlob  

---

## ⚙️ Technologies Used  

| Category | Tools / Libraries |
|-----------|------------------|
| Language | Python |
| Libraries | Pandas, NumPy, Matplotlib, Seaborn, NLTK, TextBlob, scikit-learn |
| Algorithm | Multinomial Naive Bayes |
| Feature Extraction | TF-IDF Vectorization |
| Environment | Google Colab / Jupyter Notebook |

---

## 📂 Files Included  

| File | Description |
|------|-------------|
| `Naive_Bayes.ipynb` | Main Jupyter Notebook containing code implementation |
| `blogs.csv` | Dataset containing blog text and labels |
| `README.md` | Project documentation file |

---

## 🧪 Key Steps  

### 1️⃣ Data Loading & Inspection  
- Loaded `blogs.csv` dataset  
- Displayed dataset shape, column info, and category distribution  

### 2️⃣ Text Preprocessing  
- Removed URLs, punctuation, and numeric characters  
- Tokenized and lemmatized using **WordNetLemmatizer**  
- Removed **stopwords** with NLTK  
- Created a new column `Cleaned_Text`  

### 3️⃣ Feature Extraction  
- Applied **TF-IDF Vectorizer** (`max_features=5000`, `ngram_range=(1,2)`)  
- Converted textual data into numerical vectors  

### 4️⃣ Model Building – Naive Bayes Classifier  
- Trained a **MultinomialNB** model on training data  
- Evaluated model with accuracy, precision, recall, and F1-score  
- Displayed **classification report** and **confusion matrix**  

### 5️⃣ Sentiment Analysis  
- Used **TextBlob** to calculate sentiment polarity for each blog  
- Categorized sentiment as **Positive**, **Negative**, or **Neutral**  
- Visualized sentiment distribution overall and across blog categories  

### 6️⃣ Summary Report  
- Highlighted classification accuracy and sentiment insights  
- Discussed text-based trends and model interpretability  

---

## 📊 Sample Visuals  
📈 **Category Distribution Plot**  
💬 **Sentiment Distribution by Category**  
🧩 **Confusion Matrix Heatmap**

---

## 🚀 Future Improvements  
- Experiment with **BERT or LSTM** for deeper contextual understanding  
- Use **SMOTE** for class imbalance  
- Integrate into a **Streamlit web app** for real-time blog classification  

---

## 🏷️ Tags  
`nlp` `naive-bayes` `text-classification` `sentiment-analysis` `tfidf` `textblob` `machine-learning`

---

## 👨‍💻 Author  
**Yash Sonone**  
📧 yashsonone17@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/yash-sonone-0ab717248)
