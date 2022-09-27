# Project 1: Navigation

### Introduction

You will train an agent to navigate (and collect bananas!) in a large, square world.  

![collecting_bananas](https://user-images.githubusercontent.com/114461809/192487542-54f1cd3b-c62d-4f09-8355-028ef9ee8c95.gif)


Reward for collecting a yellow banana=+1
Reward for collecting a blue banana = -1  
Goal: Collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

### Solving the environment: 
Your agent must get an average score of +13 over 100 consecutive episodes.

### Getting Started

1. Download the game environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (_For Windows users_) Check out [this link](https://support.microsoft.com/en-us/help/827218/how-to-determine-whether-a-computer-is-running-a-32-bit-version-or-64) if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (_For AWS_) If you'd like to train the agent on AWS (and have not [enabled a virtual screen](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Training-on-Amazon-Web-Service.md)), then please use [this link](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux_NoVis.zip) to obtain the environment.

2. Unzip (or decompress) the downloaded file and place it in your working folder.
3. Start by making sure that you have all the packages detailed in `environment.txt` 
4. Then, open the `Navigation_Enhanced_3.ipynb` and run the cells sequentially to initiate the process of agent interacting with environment while learning before achieving an average score of >13.0 (average over 100 episodes). 



## How to use the files in the repository

* Main files
  * Navigation_Enhanced_3.ipynb (This the only file you need to open to implement the agent)
  * model_enhanced2.py (This contains a neural network package which will be imported as a package in Navigation_Enhanced_3.ipynb)
* Packages you need to run the main files above
  * environment.txt
* Trained model weights
  * checkpoint.pth
* A PDF report describing process of exploring hyperparameter values and Neural Network architecture (along with ideas for future iterations)
  * Project 1 report - Navigation_v3.pdf   
* This README.md file

