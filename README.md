# Workflow
<ol>
  <li>Explore and analyze data </li>
  <li>Structure a 3NF schema </li>
  <li>Implement the ETL process </li>
  <li>Establish a comprehensive DBMS </li>
  <li>Design customer interaction plans </li>
</ol>

# Normalization Plan
<ul>
    <li>1NF: Eliminate repeating groups in individual tables, such as building information and document.</li>
    <li>2NF: Create separate tables for sets of values that apply to multiple records, dividing into 18 tables.</li>
    <li>3NF: Eliminate fields that do not depend on the key, such as table region and external_source.</li>
</ul>

![image](https://user-images.githubusercontent.com/102703087/202594047-738ab8dc-bc7f-4097-b199-44238b813643.png)

# ETL Process
![image](https://user-images.githubusercontent.com/102703087/202594217-861a1230-6c8b-48d0-91d9-db4cd693b94d.png)

# Interaction Plan
![image](https://user-images.githubusercontent.com/102703087/202594326-048c51b8-7627-4529-aa92-b99b63cf08bb.png)


# Conclusion
Our project aims to reduce credit fraud risk by establishing a comprehensive customer database management system, which allows the financial institution to identify and understand small business lending more effectively. 

<ul>
  <li> For the purpose of characterizing loan applicators precisely, we collected large size real financial loan data to build our relational database and developed this relational database to the third normalization form, with 23 different factors (tables). </li>
  <li> For the purpose of understanding small business lending better, it is important to reveal the driving factors behind each loan default, and we achieved this by implementing a detailed customer interaction plan. In this plan, we designed 12 analytical procedures that derive valuable insights from both the product side and the customer side to the C-level officer.</li>
</ul>

Successfully carrying out our customer interaction plan will help the institution not only reduce the loan default risk of borrowers but also expand its user population.
