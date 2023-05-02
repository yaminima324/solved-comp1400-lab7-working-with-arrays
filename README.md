Download Link: https://assignmentchef.com/product/solved-comp1400-lab7-working-with-arrays
<br>
<strong>GPA survey</strong>: Suppose that an instructor needs a piece of software to record the GPA of a class, and to find the number of students in each GPA. The software first allows the instructor to enter the number of students enrolled in the class, and then to enter the GPA of all students one by one. For each student, the input must be between 1 and 4 inclusively. Otherwise, the software displays a message as “Invalid number!” and asks for a new GPA for the same student. A sample interaction is shown below:

<strong>Sample input:</strong><sub>   </sub><strong>                                                                  Sample Output: </strong>

<table width="0">

 <tbody>

  <tr>

   <td width="341">


    <table width="0">

     <tbody>

      <tr>

       <td width="274">   Enter the number of students:</td>

       <td width="66"><strong><u>10</u></strong></td>

      </tr>

      <tr>

       <td width="274">GPA of student #1 is :</td>

       <td width="66"><strong><u>1</u></strong></td>

      </tr>

      <tr>

       <td width="274">GPA of student #2 is :</td>

       <td width="66"><strong><u>5</u></strong></td>

      </tr>

      <tr>

       <td width="274">Invalid number!GPA of student #2 is :</td>

       <td width="66"><strong> </strong><strong><u>2</u></strong></td>

      </tr>

      <tr>

       <td width="274">GPA of student #3 is :</td>

       <td width="66"><strong><u>3</u></strong></td>

      </tr>

      <tr>

       <td width="274">GPA of student #4 is :</td>

       <td width="66"><strong><u>4</u></strong></td>

      </tr>

      <tr>

       <td width="274">GPA of student #5 is :</td>

       <td width="66"><strong><u>4</u></strong></td>

      </tr>

      <tr>

       <td width="274">GPA of student #6 is :</td>

       <td width="66"><strong><u>2</u></strong></td>

      </tr>

      <tr>

       <td width="274">GPA of student #7 is :</td>

       <td width="66"><strong><u>3</u></strong></td>

      </tr>

      <tr>

       <td width="274">GPA of student #8 is :</td>

       <td width="66"><strong><u>1</u></strong></td>

      </tr>

      <tr>

       <td width="274">GPA of student #9 is :</td>

       <td width="66"><strong><u>0</u></strong></td>

      </tr>

      <tr>

       <td width="274">Invalid number!GPA of student #9 is :</td>

       <td width="66"><strong> </strong><strong><u>3</u></strong></td>

      </tr>

      <tr>

       <td width="274">GPA of student #10 is :</td>

       <td width="66"><strong><u>4</u></strong></td>

      </tr>

     </tbody>

    </table></td>

   <td width="720">


    <table width="0">

     <tbody>

      <tr>

       <td width="269">The total number of students is 10.GPA 1 — 2 student(s)GPA 2 — 2 student(s)GPA 3 — 3 student(s)GPA 4 — 3 student(s) </td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong>Note</strong>: you should trace the GPA list just once. So, you should use an array int GPAFreq[4] to store the frequencies of each GPA from 1 to 4.

<h1>Part A: RAPTOR Exercise</h1>

<ol>

 <li>Understand more about RAPTOR by watching the video clip about <strong><em><u><a href="https://www.youtube.com/watch?v=d2qlLvM4ijo">arrays</a></u></em></strong></li>

 <li>Start RAPTOR and create the flowchart of GPA survey. To save time during software development, your algorithm needs to use random number generator to simulate the input of GPAs. For example, <strong>”floor(Random*6)” </strong>produces a random number between 0 and 5.</li>

 <li>Save the flowchart to a file named “gpaSurvey.rap” in the working directory on the PC you are using.</li>

</ol>




<ol>

 <li>Demonstrate the gpaSurvey.rap file to GA/TAs and run with different input values.</li>

</ol>

<strong>Suggestion</strong>: Use subcharts to help improving the readability of the flowchart.

<strong> </strong>

<h1>Part B: C Programming Exercise</h1>

<ol>

 <li>Implement the algorithm as represented by “gpaSurvey.rap”, and write an equivalent C program that accomplishes what the flowchart does.</li>

</ol>

<em>Hints</em>: On page 173 of the textbook, an example of using random numbers is showed in the C codes of “deal.c”.

<ol>

 <li>Save your program to a file named “gpaSurvey.c” in the working directory on the PC you are using.</li>

 <li>Demonstrate the gpaSurvey.c file to GA/TAs and run with different input values.</li>

</ol>




<strong>EVALUATION: </strong>

You need to show your GA/TA the complete programs at the end of this lab, or at the beginning of your next lab. The marks you will receive for this lab are made of two parts: Lab work marks 10 and attendance marks 5. <strong>Total 15 marks</strong>.

<strong>Lab Work Mark</strong>: Your C code will be evaluated based on your solutions for the problems based on the following scheme:

<ol>

 <li>Does the code run and meet specifications?

  <ul>

   <li>Is input adequate and input data type properly validated?</li>

   <li>Is processing adequate?</li>

   <li>Is output correct and adequate?</li>

   <li>Is the code compliable? Is the code run properly?</li>

  </ul></li>

</ol>




<ol start="2">

 <li>Is the code properly commented?

  <ul>

   <li>Is the program title, programmer’s first and last name, and the date posted at the top in a multi-line comment?</li>

   <li>Is each significant step of the program properly commented?</li>

   <li>Are comments added to clarify details?</li>

   <li>Are comments clear, accurate, neatly formatted, and have no misspellings?</li>

  </ul></li>

</ol>




<ol start="3">

 <li>Is the code properly formatted?

  <ul>

   <li>Are blocks of code indented according to their parent-child relationship?</li>

   <li>Do curly braces line up vertically?</li>

   <li>Is there an empty line between significant steps (blocks) of the program?</li>

   <li>Is the width of the code contained within a reasonable limit so that minimal horizontal scrolling is required (with 800 x 600 monitor resolution), and there is minimal linewrapping when printed?</li>

   <li>Is camel-case notation used for variable, e.g. employeeLastName?</li>

  </ul></li>

</ol>