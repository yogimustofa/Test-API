TASK
Create an API testing, to test a flow of CRUD request in 1 testing flow using postman monitor.
REQUIREMENT

1.	Head to https://reqres.in/
2.	Pick any 4 endpoints to form a CRUD request
3.	Import the 4 endpoints to dedicated postman collection for this test
OBJECTIVE

1.	Order the 4 endpoint to form a CRUD inside the collection
2.	Do an API test chaining, on each endpoints to the next one, ex:
•	Endpoint #1 create a user, and generate data "id"
•	Endpoint #2 fetch the "id" from previous step , use it on the request parameter, and verify the response body and code are correct with assertions.
•	Endpoint #3 should fetch the "id", and edit the data in property "name" to something else. Verify the response body and code are correct with assertions.
•	Endpoint #4 then delete the created user in first step. Verify the status code is correct with assertions.
•	Collection should be executable inside postman "Monitor", with all result are PASSED
