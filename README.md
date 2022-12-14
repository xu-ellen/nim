# nim

1. `play.py`: play game of Nim with bot, Q-learning agent, or human
2. `nim.py`: Nim and Bot classes for game and optimal playing agent based on Sprague-Grundy
3. `q.py`: Q-learning RL agent trained on self-play
4. `nim.ipynb`: an attempt to understand the math, derive proofs, and create intuitive visualizations :)
5. `q.ipynb`: showing that Q-learning finds the most optimal gameplay for 2-heap Nim!

Code for:
- Mex function (and XOR and mex equivalence fxn)
- Calculating Sprague-Grundy values for Nim and Wythoff's Nim
- Encoding XOR and Fibonnaci sequence/Golden ratio using Nim winning positions
- Bot (optimal strategy) and Q learning

2-heap Nim:

![image](https://user-images.githubusercontent.com/56745453/201555184-41da40cb-0ad8-4f4c-9193-9f04f2d94d36.png)

Wythoff's Nim:

![image](https://user-images.githubusercontent.com/56745453/201555204-c8ddd680-1338-4e74-8a92-07c2e2e41d05.png)

Q learning:

![image](https://user-images.githubusercontent.com/56745453/202778919-3472ae9f-e377-4f4b-baf7-9933d7488471.png)

Todo:
- [x] Derive proof for Beatty's theorem (on paper, explains why golden ratio can be used to find winning solution to Wythoff's Nim)
- [x] Bot that wins every time by reducing XOR to 0 at each move
- [x] Q learning (a RL which builds table of states+actions and does a simple update based on which actions most frequently led to rewards)

Q learning update: ![Wikipedia](https://user-images.githubusercontent.com/56745453/202762079-015baaf8-47ae-4985-9259-8b6138aa2211.png)

![image](https://user-images.githubusercontent.com/56745453/202652832-c9bb443b-ad80-470b-be7f-ae9acb501d57.png)

---

Thanks to Professor Paul Zeitz for introducing this problem to me!
