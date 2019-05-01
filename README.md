#Project Mercury 

This project is intended to provide an introduction to the topic of Relativity. Relativity is a topic many find too intimidating and
therefore end up retracting their curiosity for. Here, we introduce a topic that is roughly closer or easier to understand by 
simply knowing Keplerian orbits: the trajectories of planets around our sun. Out of the planets orbiting the sun, the closest and the most 
intriguing is Mercury. It's orbit is the most eccentric out of our Solar System, and it perihelion advances change orbit positions throughout it's orbits. The reason is its proximity to the sun. As Mercury is placed in such a close distance to the sun, it's orbit behaves different to what Newtonian physics predicts. 

Overall, we created a code in Python and Javascript. The process required to plot Mercury’s trajectory is relatively simple. It’s trajectory can be plotted using the equation and format provided by C. Korber et al. in their article “A primer to numerical simulations: The perihelion motion of Mercury”. They have written this article in order to allow High School Teachers to plot Mercury Perihelion Advance by themselves for their students, and breaks down the calculation into several succinct steps. We will try to tackle it in Python, as the calculations require less confusion. 

Our objectives of this project is to further the understanding of General Relativity in something that is close to us -- a mere distance of 77 million km away from Earth. By visually showing Mercury circling around the Sun’s gravitational field influence will likely raise the familiarity of gravitational field for all. 

For starters, we have set up the following initial conditions: 
For the masses, we assume the standard of solar mass, therefore
Mass of Mercury: 1.66e-7 
Mass of Sun: 1
We have the rest as follows: 
Mercury Orbit Radius: 4.60 [Ro = 10^10m]
Mercury Orbit Speed: 5.10e-1 [Ro/time]
Base Acceleration: 9.90e-1 [Ro^3/time^2]
Orbit Period of Mercury: 8.80e1 [time]
Schwarzschild Radius of Sun: 2.95e-7 [Ro]
Specific Angular Momentum: 8.19e-7 [Ro^2] 

We had a few issues during this project. Initially, we couldn't figure out how to make use of vpython, although we eventually solved the issue through multiple trial runs. Finding the right equation to plot to simulate the movement was a struggle as well, since general relativity is a complex subject. However, online resources and several thorough readings allowed us to show Mercury orbiting around the sun. Another problem was the parameters alpha and beta. We didn't have a deep understanding of the importance of these variables and couldn't show Mercury's orbit changing. In the end, we chose the values as specified above to effectively illustrate the precession. Learning how to use GitHub had a steep learning curve as well, as neither of us have ever used it before this project. 

We hope you enjoy looking at Mercury orbiting around the sun! Thank you. 

