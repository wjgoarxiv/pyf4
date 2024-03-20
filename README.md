# pyf4
::A Python script to calculate and visualize the F4 order parameter from GROMACS trajectory::

----

This repository contains a Jupyter Notebook (`f4.ipynb`) that calculates the $F_4$ order parameter from a trajectory of water molecules and plots the $F_4$ values over the trajectory frames.

## Showcases

| 

## Features

- Calculates the $F_4$ order parameter for each frame in a water molecule trajectory
- Plots the raw $F_4$ values over the trajectory frames
- Computes and plots a moving average of the $F_4$ values for smoother visualization

## Usage

1. Make sure you have the required dependencies installed.
2. Place your water molecule trajectory file in the `source_trj` directory.
3. Run the `f4.ipynb` notebook to calculate and plot the F4 order parameter.

## Workflow

1. Decompose the `.gro` file into individual frames (if not already done).
2. Calculate the F4 order parameter for each frame.
3. Plot the raw F4 values over the trajectory frames.
4. Compute and plot a moving average of the F4 values for better visualization.

## Acknowledgements

- The F4 order parameter calculation is based on the work by [citation].
- This project utilizes the MDAnalysis library for trajectory analysis.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to explore the code and adapt it to your specific needs. If you have any questions or suggestions, please open an issue or contact me.

Happy analyzing!
