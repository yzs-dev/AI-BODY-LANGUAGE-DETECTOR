
# AI Body Language Detector 🤖🧠

A deep learning-based project that detects and interprets human body language using real-time video and pose estimation. This project leverages OpenCV, MediaPipe, and TensorFlow to classify various body language postures.

---

## 🚀 Features

* Real-time webcam integration
* Body landmark detection using MediaPipe
* Pose classification using a trained TensorFlow model
* Streamlined and interactive interface

---

## 🛠️ Tech Stack

* **Python**
* **OpenCV** – Video processing
* **MediaPipe** – Human pose detection
* **TensorFlow / Keras** – Model training and prediction
* **Pandas & NumPy** – Data handling and preprocessing
* **Matplotlib & Seaborn** – Visualization

---

## 🧪 How It Works

1. **Pose Detection:** MediaPipe extracts 33 body landmarks from a live video feed.
2. **Data Collection:** Landmarks are stored with corresponding labels (body language classes).
3. **Model Training:** A neural network is trained on the labeled data.
4. **Real-Time Inference:** The trained model classifies body language live via webcam.

---

## 📂 Repository Structure

```
📁 AI-BODY-LANGUAGE-DETECTOR
├── AI BODY LANGUAGE DETECTOR.ipynb     # Main notebook
├── data/                               # Collected landmarks (CSV)
├── model/                              # Trained model files
├── README.md
└── requirements.txt                    # Required Python packages
```

---

## 🧑‍💻 Usage

1. **Clone the repo**

   ```bash
   git clone https://github.com/yzs-dev/AI-BODY-LANGUAGE-DETECTOR.git
   cd AI-BODY-LANGUAGE-DETECTOR
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebook**
   Open and run `AI BODY LANGUAGE DETECTOR.ipynb` in Jupyter Notebook or Google Colab.

---

## 📊 Customization

* You can extend the body language labels in the dataset.
* Retrain the model with new classes using the existing pipeline.
* Add more features like gesture recognition or emotion estimation.

---

## 📎 Requirements

* Python 3.7+
* OpenCV
* MediaPipe
* TensorFlow
* Pandas, NumPy, Matplotlib, Seaborn

---

## 📜 License


Feel free to use, modify, and distribute!

---

## 🙌 Acknowledgements

* [MediaPipe](https://mediapipe.dev/)
* [TensorFlow](https://www.tensorflow.org/)
* [OpenCV](https://opencv.org/)

---

Let me know if you'd like this README with badges, a custom logo, or added deployment instructions.
