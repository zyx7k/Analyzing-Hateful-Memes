# Analyzing-Hateful-Memes
Submission for Precog Recruitment **`Task 2:`** Analyzing Hateful Memes

## Summary
This codebase uses various computer vision techniques to qualitatively and quantitatively analyze the different aspects that include and revolve around hateful memes. The analysis gives a very interesting insight into patterns, context and visual cues, all of which affect the way we pervieve memes. The project also highlights the difficulties faced in idenitfying whether a meme can be classified as hateful or not.

## How to Run
The codebase has been divided into folders corresponding to the subtasks of the main task.

**`IMPORTANT`** Before you begin, you should download the Dataset from this ([Google Drive Link](https://drive.google.com/drive/folders/1rdxxt48MBHTHIkINuIVXeGYEFFqqrP6p?usp=drive_link)) and extract it into the main folder. If you wish to use your own dataset, feel free to do so, but make sure to follow the same directory setup as the one in the link.

## Subtask 1: Object Detection
All the codes and outputs related to this task can be found in the [object Detection](Object%20Detection) folder.

## Subtask 2: Caption Impact Assessment
All the codes and outputs related to this task can be found in the [Caption Impact Assessment](Caption%20Impact%20Assessment) folder.

**`NOTE`** The [notebook](Caption%20Impact%20Assessment/Object%20Detection%20and%20Caption%20Impact%20Assessment/objectDetectionWithoutText.ipynb) when compiled and run, outputs the meme images with their text/caption removed. In my submission, I have demonstrated the model's results by running it on [this dataset](https://drive.google.com/drive/folders/1sg94bSMp-pv7z8Em854kAdhdgbk4rgOB?usp=drive_link). The output for the same can be viewed in this [Google Drive Link](https://drive.google.com/drive/folders/1GuarCer9Ui2r6jidZa6XUT77H31jr38A?usp=drive_link)

## Subtask 3: Classification System Development
All the codes and outputs related to this task can be found in the [Classification System Development](Classification%20System%20Development) folder.

## Bonus Task
All the codes and outputs related to this task can be found in the [Bonus Task](Bonus%20Task) folder.

## Paper Reading Task
The PDF Report for the paper reading task can be found [here.](Reading_Task_Report.pdf)

## Required Libraries
The following libraries need to be installed in order to run this submission

```
Python 3.10 or above
cv2
pytesseract
torch
os
string
numpy
keras_ocr
tensorflow
matplotlib
```

Run the following command in your terminal to install the required dependencies:
```python
pip install - matplotlib os torch cv2 numpy keras_ocr pyterrseract tensorflow string
```