# gossip-protocol-java
Automatically exported from code.google.com/p/gossip-protocol-java


###Basic implementation of a gossip protocol to reach agreement among members

This project allows for a specified number of members to startup and communicate its own member list using a gossip protocol. The project can reach consensus about the state of all the members and as a result is effective for fault detection. It scales well and is important for not having any single point of failure. As compared to using group communication protocols, gossip protocols can much easier handle network partitions and members that come in and out of range.

The frequency of the gossip message and the timeout of failed members is configurable.
