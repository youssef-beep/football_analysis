# Football Analysis

This project analyzes football match videos to track players and the ball, estimate their speed and distance, assign teams, and determine ball possession.

## Features

- **Object Tracking:** Tracks players and the ball using a YOLO model.
- **Camera Movement Estimation:** Estimates and compensates for camera movement.
- **View Transformation:** Transforms player and ball positions to a 2D view.
- **Speed and Distance Estimation:** Calculates the speed and distance covered by each player.
- **Team Assignment:** Assigns players to teams based on their jersey color.
- **Ball Possession:** Determines which player and team has possession of the ball.

## Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/youssef-beep/football_analysis.git
    cd football_analysis
    ```

2.  **Create and activate a virtual environment:**
    ```bash
    python -m venv venv310
    .\venv310\Scripts\activate
    ```

3.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1.  **Place your input video** in the `input_videos` directory. The video file should be named `08fd33_4.mp4` or you can change the video name in `main.py`.

2.  **Run the main script:**
    ```bash
    python main.py
    ```

3.  The output video will be saved in the `output_videos` directory as `output_video.avi`.

## Dependencies

The project uses the following major libraries:

- opencv-python
- numpy
- torch
- torchvision
- ultralytics
- supervision
- scikit-learn
- pandas

A full list of dependencies is available in `requirements.txt`.
