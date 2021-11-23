# CarRacing-v0-PPO
A Reinforcement Learning implementation for OpenAI Gym CarRacing-v0 by Proximal Policy Optimization. 
It uses a same CNN network as input for both actor and critic, and MultivariateNormal distribution 
to select and evaluate action. 

## Requirement
- pytorch
- gym

## Train
```python PPO_car_v2.py```

it would save your train model under project folder.

## Test
```python test_car.py```

It uses a pretrained model by default. Change the file path to your trained model. Change "save_gif" to "False" to save jpg files.

## Demo
<div align=center><img src="gif/CarRacing-v0.gif"/></div>




