# KAFAA – Smart Recruitment Recommendation System

KAFAA is a smart recruitment recommendation system designed to revolutionize hiring practices in Saudi Arabia. It uses Artificial Intelligence (AI), Machine Learning (ML), and Natural Language Processing (NLP) to intelligently match candidates with suitable job opportunities—helping both job seekers and employers make better decisions.

---

## 🎯 Objectives

- Minimize mismatches between candidate qualifications and job requirements  
- Increase the visibility of job postings  
- Promote transparency and fairness in recruitment  
- Automate tedious steps in hiring workflows  
- Enhance candidate engagement with personalized job recommendations

---

## 🇸🇦 Vision Alignment

KAFAA directly supports **Saudi Vision 2030** by:

- Enhancing labor market efficiency  
- Accelerating economic diversification and digital transformation  
- Strengthening national human capital  
- Reducing unemployment through smart recruitment solutions

---

## ✨ Features

- **Smart Job Matching**: ML & NLP-powered personalized job recommendations  
- **Semantic Search**: Understands context and intent using modern BERT-based embeddings  
- **Hybrid Filtering**: Combines collaborative, content-based, and semantic techniques  
- **User-Friendly Interface**: A modern, responsive interface built for ease of use  

---

## 🏗 System Architecture

The system includes four core recommendation models:

1. **User-Based Collaborative Filtering**  
   - Simulated interactions and ranked recommendations via LightGBM

2. **Text-Based Filtering**  
   - Uses TF-IDF and cosine similarity for basic job-resume text matching

3. **Semantic AI Matching**  
   - Leverages sentence embeddings (MiniLM, RoBERTa) with BIRCH + FAISS for scalable search

4. **Advanced Hybrid Filtering**  
   - Combines structured features (e.g., location, skills) with semantic vectors

---

## 🧠 Backend Technologies

- **Language:** Python  
- **Libraries & Tools:**  
  - `LightGBM` – Learning-to-rank  
  - `FAISS` – Fast Approximate Nearest Neighbor Search  
  - `BIRCH` – Clustering for grouping candidates  
  - `MongoDB` – NoSQL database  
  - `KNN`, `SVM` – Traditional ML models  
  - `SVD` – Dimensionality reduction  
  - `Min-Max Normalization` – Feature scaling

- **NLP & Embeddings:**  
  - `TF-IDF`, `BM25` – Text weighting and ranking  
  - `Word2Vec` – Word-level embeddings  
  - `Named Entity Recognition (NER)` – Extracts relevant skills, roles, companies  
  - `RoBERTa` – Deep contextual language model  
  - `All-MiniLM-L6-v2` – Efficient transformer sentence embeddings  
  - `Modern BERT` – For advanced semantic understanding  
  - `DSSM` – Deep Semantic Structure Modeling (future scope)

---

## 💻 Frontend Technologies

- **Languages:**  
  - `HTML5`  
  - `CSS3`  
  - `JavaScript (ES6+)`

- **Tools:**  
  - `Figma` – UI/UX Prototyping
    
---


## 👩‍💻 Team
- Sarah Alotaibi
- Sema Alshamrani
- Yasmeen Ammar 
- Deema Alshehri
- Dhiyaa Alsalem

---

## Supervisor
Dr. Manel Ayadi

---

## 🏫 Institution

Princess Nourah bint Abdulrahman University  
College of Computer and Information Sciences  
Data Science and Analytics Program  
Riyadh, Kingdom of Saudi Arabia

---

## 📄 License

This project is for academic and educational purposes only.
