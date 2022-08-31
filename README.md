# SpringBootExample  Using Eclipse IDE


1.Create a new SpringBoot starter project
2.create packages(com,dao,model,service)
<img width="191" alt="Screenshot 2022-08-31 at 18 11 10" src="https://user-images.githubusercontent.com/74420607/187738962-94d88958-09c1-4d67-a776-3963788e0754.png">
<hr>
3.configure the application properties file
<img width="399" alt="Screenshot 2022-08-31 at 18 11 38" src="https://user-images.githubusercontent.com/74420607/187739043-df50ede8-001a-41d2-b8ce-09ab10684cd1.png">
<hr>
4.create the model of your application(ex. book)with constructor,setter,getter, toString method
<img width="467" alt="Screenshot 2022-08-31 at 18 13 17" src="https://user-images.githubusercontent.com/74420607/187739299-f5d4cdef-b00e-4d38-85b1-d3d282d55f55.png">
<hr>
5.on DAO package create bookDAO and bookDAOImplementation
<img width="243" alt="Screenshot 2022-08-31 at 18 15 16" src="https://user-images.githubusercontent.com/74420607/187739639-0e4cc43f-acc3-4ae8-87b7-dbbd9d7a07a1.png">

<img width="245" alt="Screenshot 2022-08-31 at 18 17 22" src="https://user-images.githubusercontent.com/74420607/187739960-8208a59b-56dd-4430-9551-ab7009221ce9.png">

<img width="477" alt="Screenshot 2022-08-31 at 18 18 58" src="https://user-images.githubusercontent.com/74420607/187740211-eec4838d-73e0-402d-8439-78f96f2cacc7.png">
<hr>
6.on  Service package create bookService and serviceImplementation
<img width="275" alt="Screenshot 2022-08-31 at 18 20 58" src="https://user-images.githubusercontent.com/74420607/187740516-52b96066-a0cc-4749-9c54-1648c7798fe7.png">
<img width="271" alt="Screenshot 2022-08-31 at 18 21 25" src="https://user-images.githubusercontent.com/74420607/187740591-4d4bc59e-f17b-4dfe-9c9a-0932dd7b957a.png">
<img width="468" alt="Screenshot 2022-08-31 at 18 21 38" src="https://user-images.githubusercontent.com/74420607/187740620-28e25491-4be8-4b6f-a721-4c61eb423005.png">
<hr>
7.lets fill the main file on com package
<img width="577" alt="Screenshot 2022-08-31 at 18 23 59" src="https://user-images.githubusercontent.com/74420607/187741011-ee9014af-d2db-4fdd-a8b7-7fd6a31147d4.png">
<hr>


COM PACKAGE Key note:
1.Implement the CommandLineRunner (necessary for running all the springBoot code and allow to implement the public void run method)
On main file call the following annotation: <br>
 -@SpringBootApplication
 -@Autowired (dependency injection of the bookService)
 <hr>
 
 DAO PACKAGE Key note:
 call the @Repository Annotation
 call the @Autowired Annotation(call the jdbcTemplate)
 <hr>
 
 
 SERVICE PACKAGE Key note:
 call the @Service Annotation
 call the @Autowired Annotation(call the bookDAO)
 <hr>
 
 
 
 
 
 
 
