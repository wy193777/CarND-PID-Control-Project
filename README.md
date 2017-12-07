# Reflection

## Effects of P, I, D

### P

P is simply proportional parameter multiplied to error. So it control how fast a controller will move to desired status.

### I

I is the error over time multiplied by integral parameter. So if the output of the wheel steer has a constant error, this error will be eliminated after a short time if I parameter existed.

### D

D is kind of like predict the future. Because it's proportional to change rate of the error. 

## Hyperparameters Choosen

P: 0.1, I: 0.002, D: 2.5. I picked them manually. The basic way is increase P and D together until the car can steer enough when on curved roads. Then I will only increase D until the car can drive straight on the straight.

