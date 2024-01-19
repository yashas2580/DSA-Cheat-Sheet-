# DSA Cheat Sheet
<h1>Arrays</h1>
<p>An array is a series of elements of the same type placed in contiguous memory locations that can be individually referenced by adding an index to a unique identifier.

That means that, for example, five values of type int can be declared as an array without having to declare 5 different variables (each with its own identifier). Instead, using an array, the five int values are stored in contiguous memory locations, and all five can be accessed using the same identifier, with the proper index.</p>
<h2> Declaration of Arrays</h2>
<p>Arrays can be declared by using the line or code.</p>
<p><b> int array_name[size of array]; </b></p>
<p> Example: <b>int arr[5]; </b> Here array of name "arr" is created and the size of array is "5". </p>

<h2><b> Initialization of array </b> </h2>
<p>In C++ there are four types of array initialization. They are :-<br> 1.) Declaration of array with size and elements in array are initially declared : Example:-<b> int arr[5]={1,2,3,4,5}; .</b>
<br> 2.)Declaration of array without size and elements. Example:- <b>int arr[]={};</b> Here array elements are initialized with zero .<br>
  3.) Declaration of array and taking input from user. Example:- <b> inr arr[n];</b> Here the array elements input is taken from the user.
 </p>
<h2>Accesing Elements in an array</h2>
<p>In C++ the elements in an array can be accessed using either for loop or by directly using the index of the element. <br>
Example: Consider the given array of size 5. int arr[5]={1,2,3,4,5};.<br>
Here if I want to access the element 5 I can directly use the index of it to access the element from the array. Here I can use arr[4] to get the value 5 from the array.<br>
Second Case by using the for loop here the size of the array is 5. So run a for loop starting from 0 to the index of the last element i.e 4. 
</p>
<h2>Vectors in C++</h2>
<p> Vectors are variable sized array which doubles its size when completely filled.</p>
<h2>Declaration of Vectors</h2>
<p>Vectors can be declared by using this genral syntax </p>
<p><code> vector<data_type>vector_name</code></p>
