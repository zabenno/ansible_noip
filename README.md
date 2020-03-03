# Overview

This role creates a container and mounts a persistent configuration file to keep the DNS response for the IP address up to date. It requires the default login credentials to be overridden in order to function.

Parameters to be overridden:

noip_username

noip_password

# Assumptions
As noip doesn't allow for automated CLI based selection of FQDNs it is assumed that all FQDNs within the account are to be assigned to the clients IP address. This may be changed in the future if I find a way.
