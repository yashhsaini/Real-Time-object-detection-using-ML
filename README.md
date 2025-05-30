# Real-Time Object Detection using YOLOv8

Developed a real-time object detection system using YOLOv8 and OpenCV that processes live video feeds to identify 80+ object classes with dynamic visualization and confidence scoring.

## Features
- Real-time object detection using YOLOv8
- Full-screen display with dynamic bounding boxes
- Confidence score display for detected objects
- Automatic fallback to OpenCV DNN if YOLO fails
- Support for 80+ object classes
- Robust error handling and automatic model downloads

## Requirements
- Python 3.8+
- OpenCV
- Ultralytics YOLOv8
- Webcam

## Installation
1. Clone the repository
```bash
git clone https://github.com/yashhsaini/Real-Time-object-detection-using-ML.git
```

2. Create a virtual environment:
```bash
python -m venv yolo_env
yolo_env\Scripts\activate  # On Windows
```

3. Install requirements:
```bash
pip install -r requirements.txt
```

## Usage
Run the script:
```bash
python webcam.py
```

Press 'q' to exit the application.

## Technical Details
- Uses YOLOv8 nano model for efficient processing
- Implements OpenCV for video capture and display
- Includes automatic model download and initialization
- Features real-time bounding box rendering and labeling

## Author
- Yash Saini

