#**Pewlett-Hackard-Analysis**
##**Overview of the analysis**
In this project, we are using SQL queries to create tables and analyse datasets of Pewlett Hackard company. Pewlett Hackard is a huge company where several thousands of employees are working. The company is planning to provide a retirement package for their employees who are approaching their retirement age. On the other hand, the positions of the retired employees require to be filled out. We are assisting Bobby, the HR analysis to create a list of the number and information of the employees who are getting retired.
We, first, created a diagram where shows the relationship between our datasets. Then, using the diagram (shown below), we created a table for each dataset. Afterwards, using SQL queries, we selected and filtered the data to analyse the information regarding the number of retiring employees, their personal information as well as their current titles.
![EmployeeDB.png](https://github.com/zkt2018/Pewlett-Hackard-Analysis/blob/main/Data/EmployeeDB.png)
##**Results**
In the two deliverables, we created two lists, one to show the number of retirement-age employees and their latest position before retirement, and the other one to get the list of eligible employees for the mentorship program.
Through the first deliverable we create a table to display the latest position each of these employees have.
Afterwards, we created another table to count the number of employees in the retirement age which reveals the three top demanding positions that require to be filled out are Senior Engineer, Senior Staff, and Engineers.
Throughout the second deliverable, we created the Mentorship Eligibility data table. This table lists all the employees who were born within 1965. To get this list, we used Inner Join between three different tables.
The final table in deliverable 2 displays the employees who are eligible to be trained to fill out the positions.
##**Summary**
###**How many roles will need to be filled as the "silver tsunami" begins to make an impact?**
Based on the analysis results, there will be many vacancies within seven job titles that require to be filled. The image below shows the number of required positions in each job title.
![opening_roles.png](https://github.com/zkt2018/Pewlett-Hackard-Analysis/blob/main/Data/opening_roles.png)

###**Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?**
Comparing the number of retiring employees with the number of employees to be trained, there are many mentors that can provide training to the eligible future employees.
The queries created during this project provide a good insight regarding the number of employees who are getting retired and the ones who are eligible to be trained for the vacancies. The datasets can still be analysed by adding other queries, such as counting the number of eligible employees.
In addition, as the employees are located in different areas around the world, that would be beneficial to get the locations of the employees, both the retiring and the eligibles for the mentorship program.
