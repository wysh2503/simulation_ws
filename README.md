# simulation_ws

Simulation Workspace tutorial

Dependencies for the package:
Xacro - sudo apt-get install ros-melodic-xacro
Gazebo - sudo apt-get install ros-melodic-gazebo-ros

# First exercise
## Clone, build and run the ROS package
$ git clone https://github.com/PranaliDesai/robomechtrix_ws.git

$ cd robomechtrix_ws

$ git checkout URDF-1

$ catkin_make

$ source devel/setup.bash

$ roslaunch trixy world.launch

# Second exercise
## build and run the ROS package
$ cd robomechtrix_ws

$ git checkout URDF-2

$ catkin_make

$ source devel/setup.bash

$ roslaunch trixy world.launch

# Third exercise
## build and run the ROS package
$ cd robomechtrix_ws
$ git checkout URDF-3
$ catkin_make
$ source devel/setup.bash
$ roslaunch trixy world.launch
