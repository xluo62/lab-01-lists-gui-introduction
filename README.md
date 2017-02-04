# Lab 01 - Lists and GUI Introduction
##1. In an ideal scenario, what other methods should be overridden to improve performance?
       
##2. Why is the iteration of an ArrayList and LinkedList not the same speed (not complexity, actual speed)? Which one is most likely faster?
    ArrayList is pretty fast compared to the LinkedList.For example, get(int index) in ArrayList gives the performance of O(1) while LinkedList performance is O(n).
##3. Is the big-Oh complexity of the four main operations identical between the List types (add(), remove(), get() and set())?
    ArrayList: add()=O(n), remove()=O(n),get()=O(1),set()=O(1);
    LinkedList: add()=O(n),remove()=O(n),get()=O(n),set()=O(n);
##4. Describe the benefit(s) of the tests provided.
    The benefits of this test are to help us get familiar with all methods and usages in the arraylist and linkedlist in java, and help us understand about these two data structures better.
##1. Why is FXML used over raw code?
##2. What is the benefit of using SceneBuilder?
    ScenBuilder can make you create an user interface way faster, since it can generate the FXML source code when you create the user interface. ScenBuilder creates a quick prototype to get feedback.
##3. What are a callbacks and why does JavaFX use them?
    The Callback interface is designed to allow for a common, reusable interface to exist for defining APIs that requires a call back in certain situations.
