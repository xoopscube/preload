README
====

# Preload

The **Delegate** and **Preload** mechanisms of XOOPSCube.

## Delegate

**Delegate** is a mechanism in XOOPSCube that safely encapsulates a method, similar to a function pointer in C and C++. Unlike C function pointers, delegates are object-oriented, type safe, and secure. It is a technique where an object expresses certain behavior to the outside but in reality delegates responsibility for implementing that behaviour to an associated object. This sounds at first very similar to the proxy pattern, but it serves a much different purpose. Delegation is an abstraction mechanism which centralizes object (method) behaviour. It can be seen in general as an alternative to inheritance. The same functionality can also be accomplished with interfaces, however sometimes the relationship you want between two classes is actually one of containment rather than inheritance.

**Applicability / Uses**

Use the delegation pattern when:

+ you need to reduce the coupling of methods to their class
+ you have components that behave identically, but realize that this situation can change in the future.

Generally spoken: use delegation as alternative to inheritance. Inheritance is a good strategy, when a close relationship exist in between parent and child object, however, inheritance couples objects very closely. Often, delegation is the more flexible way to express a relationship between classes.

This pattern is also known as "proxy chains". Several other design patterns use delegation - the State, Strategy and Visitor Patterns depend on it.

**Related Patterns**

Decorator: is similar to delegation and uses it heavily to accomplish its task.
Delegation is very common, it is used by many other pattern like Visitor, Observer, Strategy, and Event Listener.

## Preload

**Preload** is a mechanism to enable preprocessing before the module execution.

**Delegate** and **Preload** are inherently different mechanisms and can be used independently.

There are many single-file hacks to change or extend a module processing and behavior using **Delegate** within **Preload** mechanism.

Learn more about **Preload** and how to implement delegates from the Wiki documentation examples.

