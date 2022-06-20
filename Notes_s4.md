## REST: REpresentational State Transfer 
State means data 
REpresentational means formats (such as xml, json, yaml, html, etc)
Transfer means carry data between consumer and provider using HTTP protocol 

REST API is an intermediary application programming interface that enables two applications to communicate with each other over HTTP, mush like how servers communicate to browsers. 
The REST architectural style has quickly become very popular over the world for designing and architecting applications that can communciate. 
The need for REST APIs increased a lot with the drastic increase of mobile devices. It become logical to build REST APIs and let the web and mobile clients consume the API instead of developing separate applications. 

## REST Architectural Constraints 
An API has following constraints is known as RESTful API: 
1. client-server architecture: the client is the front-end and the server is the back-end of the service. It is important to note that both of these entities are independenty of each other. 
2. Stateless: no data should be stored on the server during the processing of the request transfer. The state of the session should be saved at the client's end.
3. Cacheable: Client should have the ability to store responses in a cache. This greatly improves the performance of the API.
4. Uniform interface: this constraint indicates a generic interface to manage all the interactions between the client and serve in a unified way, which simplifies and decouples the architecturej.
5. Layered system: serve can have multiple layers for implementation. This layered architecture helps to improve scalability by enabling load balancing.
6. Code on demand: this constraint is optional. This constraint indicates that the functionality of the client applications can be extended at runtime by allowing a code download from the server and executing the code. 

## REST Key concepts 
Resource 
Sub-resource
URI
HTTP Methods 
HTTP Status Codes
