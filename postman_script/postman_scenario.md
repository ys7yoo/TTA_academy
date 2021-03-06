script collection:
https://www.getpostman.com/collections/95e465d8ab6a8330591c


## AE Registration
* preset AE-ID
* dynamic AE-ID allocation

## container 
* single container w/o any optional config
* nested container
* container w/ 'mni' (max number of instance)

## contentInstance 
* instance creation
* instance creations until 'cni' = 'mni' 
* latest / oldest retrieval
* latest / oldest removal

## subscription 
* subscription (notification over MQTT)
* child creation event
* target update event
* serialization type (XML, JSON)
* notification object observation

## discovery
* basic discovery w/o any filter conditions ('fu'=1)
* discovery with resource type ('ty')
* discovery with level ('lvl')
* discovery with creation time ('cra')
* retrieval with rcn=4
* retrieval with rcn=4 & ty=?

## group
* discover containers (+ create instance)
* container group
* latest instance group

## dashboard app - freeboard
* latest instance(s) of temp. sensor readings
