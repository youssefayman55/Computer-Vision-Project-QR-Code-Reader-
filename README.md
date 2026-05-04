# 🔍 Real-Time QR Code Reader using OpenCV & Pyzbar

## 🧠 Overview

This project is a **real-time QR code detection and decoding system** باستخدام كاميرا الجهاز.
It captures live video and extracts data from QR codes instantly using the **Pyzbar library**.

The system detects QR codes in each frame and prints the decoded content in real time.

---

## 🚀 Features

* 🎥 Real-time QR code detection باستخدام webcam
* 🔍 Fast and accurate decoding
* 🧾 Extract and display QR code data instantly
* ⚡ Lightweight and efficient implementation

---

## 🛠️ Technologies Used

* Python 🐍
* OpenCV (Video Processing)
* Pyzbar (Barcode & QR Code Decoding)

---

## 📂 Project Structure

```id="x8n3qw"
├── app.py
└── README.md
```

---

## ▶️ How to Run

### 1. Install Dependencies

```bash id="k2p7mz"
pip install opencv-python pyzbar
```

### 2. Run the Application

```bash id="n4v9yt"
python app.py
```

---

## 🎯 How It Works

* The webcam captures live video frames
* Each frame is processed using Pyzbar
* If a QR code is detected:

  * The encoded data is extracted
  * The decoded text is printed in the console

---

## 📸 Output

* Displays live video stream
* Prints decoded QR code data in real time

---

## 💡 Use Cases

* QR-based authentication systems 🔐
* Product tracking and inventory 📦
* Contactless data sharing 📲
* Event check-in systems 🎫

---

## 💡 Future Improvements

* Draw bounding box around detected QR codes
* Display decoded text on the video frame
* Save scanned data to a file or database
* Support barcode formats in addition to QR codes

---

## 👨‍💻 Author

**Youssef Ayman**
AI Engineer & Data Scientist

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!
