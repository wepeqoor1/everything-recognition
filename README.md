# everything-recognition
Search your face with webcam.

## Environment requirements
Python3.10+

## How to install
```bash
$ pip install -r requirements.txt
```

## How to use
```bash
$ python3 run.py
```

## Thesaurus
Cascad - method for detecting objects in an image based on machine learning.

## haarcascades/
Data with cascades

## config.py
Stores cascade configurations.

## run.py
Searches in the file `config.py ` active configurations with cascades.  
Launches the webcam on your computer. If the webcam is not running, it displays on the screen:  `Couldn't find your webcam... Sorry :c`  
Converts a frame from RGB to Gray.  
Defines the areas of recognition of elements in the frame, depending on the type of cascade (smile, eyes, head, full body).  
Draws rectangles in the frame depending on the type of cascade.  
If the user presses the `q` button, it closes the webcam frame.



## Project Goals
The code is written for educational purposes on online-course for web-developers dvmn.org.

