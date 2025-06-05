# MultiTaskNLP: Unified Model for NER, Sentiment & Emotion Analysis

**MultiTaskNLP** is a deep learning project designed to solve multiple natural language processing tasks — Named Entity Recognition (NER), Sentiment Classification, and Emotion Detection — simultaneously using a shared encoder architecture. The approach leverages multitask learning to improve performance across all tasks by utilizing shared representations.

## 📺 Demo

[![Watch the Demo Video](https://img.youtube.com/vi/bZgfwICfWOs/0.jpg)](https://www.youtube.com/watch?v=bZgfwICfWOs)


## 🎯 Key Features

- 🧠 **Multitask Learning**: One model handles multiple NLP tasks.
- 🤗 **Transformers & Tokenization**: Built on Hugging Face and PyTorch.
- 🏷️ **NER, Sentiment, Emotion Detection**: Trained on separate task-specific heads.
- 📊 **Evaluation & Metrics**: Precision, recall, F1, and loss per task.
- 📈 **Plots & Insights**: Loss curves and task-wise accuracy reporting.

## 🛠️ Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- Scikit-learn
- Matplotlib
- Pandas & NumPy

## 🧪 Tasks

| Task          | Description                          | Output Labels             |
|---------------|--------------------------------------|---------------------------|
| NER           | Identify named entities in text      | PER, LOC, ORG, MISC       |
| Sentiment     | Classify sentiment                   | Positive, Negative, Neutral |
| Emotion       | Detect emotional tone                | Joy, Anger, Sadness, etc. |

## 🧬 Model Architecture

- **Shared Encoder**: BERT-based encoder
- **Task-Specific Heads**: Separate linear heads for each NLP task
- **Loss Function**: Sum of cross-entropy losses across all tasks


