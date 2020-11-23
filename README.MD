[//]: # (Image References)

[image1]: https://video.udacity-data.com/topher/2018/June/5b1ab4b0_banana/banana.gif "bananaLover"
# Deep Reinforcement Learning Nanodegree Project 1 Navigation
This repository contains submission of the project 1 to Udacity's [Deep Reinforcement Learning Nanodegree](https://www.udacity.com/course/deep-reinforcement-learning-nanodegree--nd893) program.
![bananaLover][image1]
### Problem description
This implementation of deep Q-networks to navigate a large, square world and collect the yellow bananas at the same time.
A reward of +1 is provided for collecting a yellow banana and -1 is provided for collecting a blue banana. Thus, the goal is to collect as much yellow banana as possible.
#### states
There are 37 continuous states, including agent's velocity, ray-based perception around the agent's forward direction.
#### actions
There are 4 discrete actions, they are
- move forward
- move backward
- turn left
- turn right

#### goal
The environment can be considered as solved when the agent has more than 15 points over 100 consecutive episode.

### Getting Started
#### local environment set up
1. Create and activate a new environment with Python 3.6 using  [Anaconda](https://www.anaconda.com/).
  - **Linux** or **Mac**
  ```bash
  conda create --name drlnd python=3.6
  source activate drlnd
  ```
  -**Windows**
  ```bash
  conda create --name drlnd python=3.6
  activate drlnd
  ```
2. Install OpenAI gym, the instruction can be find [here](https://github.com/openai/gym)
3. Install **classic control** environment group by following the instructions [here](https://github.com/openai/gym#classic-control)
4. Install the **box2d** environment by following the instructions [here](https://github.com/openai/gym#box2d).


As this submission is done using the workspace provided by the Udacity, the Unity environment is not included. If you wish to interact with the Unity environment, feel free to download the compiled Unity environment here.
- Linux: [Click Here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
- Mac OSX: [Click Here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
- Windows (64 bit): [Click Here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)   

After you have downloaded these compiled Unity environment, you need to specify the file path in the line of `Navigation.ipynb`
### Instructions
follow the instruction of `Navigation.ipynb`, simply run the code cell with sequential manner.
**Note**: please run the Jupyter notebook under drlnd environment.


### Results
In the end, the agent have more than 15 points over 100 consecutive episodes.
