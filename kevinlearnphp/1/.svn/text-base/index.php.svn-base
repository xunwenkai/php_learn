<html>
	<body>
		<p>

		<?php
			/*	Here introduce the differences between print and echo;

			echo "My very first php file.","<br>";
			print("This line is output by print func");
			echo "<br>","This line is output by echo and with a change line character";
			*/
			
			
			// var_dump("Kevin");

			/*	define var and use var

			$myText = "This is my first php file, and i am defining my first var";
			$myNumber = 53;
			print($myText);
			print("<br>");
			print($myNumber);
			print("<br>");
			print("output by print");
			print("<br>");

			echo $myText,"<br>",$myNumber,"<br>","output by echo"; 
			*/

			/* concat string and get the position of substring in a string;

			$nameBoy = "xunwenkai";
			$nameGirl = "luozhaozhao";
			$conCatNames = $nameBoy." & ".$nameGirl;

			echo "the length of ", $conCatNames, " is ", strlen($conCatNames),"<br>";

			echo "zhaozhao is the ", strpos($conCatNames, "zhaozhao"), " of ", $conCatNames;
			*/

			/* concat 2 numbers with x.=y;

			$x = 2;
			$y = 3;
			$y.=x;
			echo $y;
			*/

			/* test if else 

			$d = date("D");
			
			if ($d == "Sat" || $d == "Sun")
			echo("Have a nice weekend!");
			else
				echo "Good good study, day day up.";
			*/
		
			/* switch case break default
			$x = 1;
			switch ($x) {
				case '1':
					echo "Number 1";
					break;

				case '2':
					echo "Number 2";
					break;
				
				default:
					echo "No number match";
					break;
			}
			*/

			/* Define array with numbers.
			$names = array("Kevin", "Suzan", "Lucy", "Lily");
			echo $names[0], " ", $names[1], " ", $names[2], " ", $names[3], "<br>";
			*/

			/* get array value by relevance quote
			$ages = array('Kevin' =>28 ,'Suzan' =>26, 'Lucy' =>27, 'Lily' =>25 );
			echo "Kevin is ", $ages[Kevin], "years old.(this line output by arrayname) ", "<br>";
			// echo "Kevin is ", $ages[0], "years old.(this line output by arraynumber) ", "<br>";
			*/

			/* revelance and dimensions array
			$qvodPlayer = array('Files' => array("Video", "Music", "Pictures"), 
				'Website' => array("Flag", "Bookmark", "Hotsite"),
				'Radar' => array("Map", "List"),
				'Arround' => array("News", "History"));

			echo($qvodPlayer[Files][0]);

			*/

			/* while loop
			$counter = 1;
			while ($counter <= 10) {
				echo "counter comes to ", $counter, "<br>";
				$counter++;
			}
			*/

			/* do...while loop
			$counter = 0;

			do {
				$counter++;
				echo "counter comes to ", $counter, "<br>";
			} while ($counter < 10);
			*/

			/* for loop

			for ($i=1; $i<=5; $i++)
			{
			  echo "Hello World!<br />";
			}
			*/

			/* foreach loop

			$bank = array('Kevin' =>100 ,'Suzan' => 200, 'Lucy' => 150, 'Lily' => -100 );

			foreach ($bank as $value) {
				echo $bank, " can be borrowed ", $value, " dollors", "<br>";
			}
			*/

			/* function with a parameter
			function writeMyName($name){
				echo "my name is ", $name, "<br>";
			}

			echo "What is your name?", "<br>";
			writeMyName("Kevin");
			*/

			/* function with return values
			function getFamilyNames($nameBoy, $nameGirl){
				$familyName = $nameBoy." ".$nameGirl;
				return $familyName."<br>";
			}

			echo(getFamilyNames("Kevin", "Suzan"));
			echo(getFamilyNames("xunwenkai", "luozhaozhao"));
			*/


		?>

		<!-- a form post to another page
		<form action="welcome.php" method="post">
			Name: <input type="text" name="name" />
			Age:  <input type="text" name="age" />
				  <input type="submit" />
		</form> -->

		<!-- a form post to itself
		<form action="index.php" method="post">
			Name: <input type="text" name="name" />
			Age:  <input type="text" name="age" />
				  <input type="submit" /> -->
	  	<?php 

	  	/* get user input and verify it in page
	  		function verifyNameAge($name, $age){
	  			if ($name == "xunwenkai" && $age == 28) {
	  				return "pass";
	  			}
	  			elseif ($name == "xunwenkai") {
	  				return "age is wrong";
	  			}
	  			elseif ($age == 28) {
	  				return "name is wrong";
	  			}
	  			else 
	  				return "name and age are wrong";
	  		}
	  		echo verifyNameAge($_POST["name"], $_POST["age"]);
  		*/


  		?>
		
		<!-- a form to get name and age
  		
  		<form name="myForm" action="welcome.php" method="get" >
  			Name:	<input type="text" name="name" />
			Age:	<input type="text" name="age" />
					<input type="submit" />
  		</form>
 		-->

 		<?php
 			/**
 			* define cart with add item and remove item
 			*/
 			// class cart
 			// {
 			// 	var $inCart;
 				
 			// 	function addItem($item, $num)
 			// 	{
 			// 		$this->inCart['$item'] += $num;
 			// 	}

 			// 	function removeItem($item, $num){
 			// 		if($this->$inCart['item'] > $num)
 			// 		{
 			// 			$this->$inCart['item'] -= $num;
 			// 			return ture;
				// 	}
 			// 		elseif ($this->$inCart['item'] == $num) 
				// 	{
 			// 			unset($this->$inCart['$item']);
 			// 			return ture;
				// 	}
				// 	else
				// 		return false;
 			// 	}
 			// }
 		
 		/**
 		* define a class
 		*/
 		// class cellPhone
 		// {
 		// 	public $number;
 		// 	public $shipDate;
 			
 		// 	public function __construct($num, $ship)
 		// 	{
 		// 		$this->number = $num;
 		// 		$this->shipDate = $ship;
 		// 	}

 		// 	public function dial($num){
 		// 		echo "You are dialing ", $num, ". Hold on for a moment.", "<br>";
 		// 	}

 		// }

 		// $kevin_s_cellPhone = new cellPhone("13927472994", "20080909");
 		// // $kevin_s_cellPhone->dial($kevin_s_cellPhone->number);

 		// // var_dump($kevin_s_cellPhone);
 		// // echo(trim($kevin_s_cellPhone->shipDate));

 		// echo(time());

 		$withLuozong = "罗总你好";
 		$withoutLuozong = "xunwenkai";

 		if(!strpos($withoutLuozong, "罗总"))
 			echo $withoutLuozong, " doesnot include luozong";
 		else
 			echo $withoutLuozong, " includes luozong";

 		?>	


 	</body>
</html>