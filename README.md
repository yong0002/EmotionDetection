# EmotionDetection
This is an emotion detection software where it will predict the 5 basic emotions of a person which are neutral, sad, happy, angry and fear.
The timestamps of the video are later annotated so you are able to know the emotion of the person at a particular time and will produce a video with annotated emotions.

# Requirements
1)Set up PyCharm and download Python version 3.7
Pycharm: https://www.jetbrains.com/pycharm/
Python : https://www.python.org/downloads/

2) Make sure to install pip as we are require to use this to install all the libraries.
pip: https://www.geeksforgeeks.org/how-to-install-pip-on-windows/#:~:text=Download%20and%20Install%20pip%3A&text=Download%20the%20get%2Dpip.py,where%20the%20above%20file%20exists.&text=and%20wait%20through%20the%20installation,now%20installed%20on%20your%20system.

3) After install pip, you are required to install all the libraries below with their versions
pip install (library)==(version)
library:numpy version:1.20.0
library opencv version:4.5.3.56
library moviepy latest
library keras version:2.2.4
library tensorflow version:1.13.2
library matplotlib latest
library h5py version:2.10.0

4)Run GUI.py to start

Steps by steps:
1)Register an account to login, and later login with your credentials
![image](https://user-images.githubusercontent.com/58330925/162221829-ba173707-9e3f-4c2b-ab4c-8280f503ead6.png)

2) Click the upload button and upload whichever video you want
![image](https://user-images.githubusercontent.com/58330925/162221926-8ae00882-a53d-49d0-9901-186a2d7b2f33.png)

3)Wait for a while, while the video is being processed and annotated

4)The timestamps of the emotion of the person in a video is annotated. You can click play video to play the annotated video.
Make sure to have a video player installed in
![image](https://user-images.githubusercontent.com/58330925/162222250-53927838-360f-40b6-99e9-28b75885a8e2.png)


** Video size being processed is at 4 to 5 seconds, please update the value in the file if you want to process the full video

