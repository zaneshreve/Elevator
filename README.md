# Elevator

Okay, so we've got a three-story building. How do elevators work?

If we're on the first floor, we can only go up to either the second or third. That decision is made once we're in the elevator.

If we're on the third floor, we can only go down to either the first or second floor. Again, that decision is made in the elevator.

If we're on the second floor, the up/down decision essentially determines what our destination is. 

So, we can check our destination direction first. If it's up, we know we're not going to the first floor. Likewise, if it's down then we know we're not going to the third floor. Secondly, we can check the destination floor. This won't *always* be necessary, but required in some cases. Plus, when more floors are added, the case of up/down determining the destination will no longer exist.


