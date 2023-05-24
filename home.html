

<?php 
include "db_conn.php";

session_start();

if (isset($_SESSION['id']) && isset($_SESSION['user_name'])) {

 ?>

<!DOCTYPE html>

<html>

<head>

    <title>HOME</title>

    <link rel="stylesheet" type="text/css" href="style.css">

</head>

<body>

     <h1>Bonjour  Mr, <?php echo $_SESSION['name']; ?></h1>
     <?php 
       $sql = "SELECT * FROM module";
       $result = mysqli_query($conn, $sql);
       if (mysqli_num_rows($result) >= 1) {           ?>  
<form action="abs.php" method="post">
       <label >Choisir votre module:</label>

<select name ="smod" id="smod">
    <option value="">--Veuillez choisir un module--</option>
    <?php 
    while($row = mysqli_fetch_assoc($result)) {  
     $r = $row['nom_mod'];
     $r1 = $row['id_mod'];
    echo "<option value=$r1> $r </option>";   
  
    } 
   ?> 
    
</select>
<label >Choisir la sp&eacutecialit&eacute:</label>
<select name ="sspec" id="sspec">
    <option value="">--Veuillez choisir une sp&eacutecialit&eacute--</option>
   

    <option value='1'> 1 ann&eacutee G industrielle </option>;   
    <option value='2'> 2 ann&eacutee G industrielle </option>;
    <option value='3'> 3 ann&eacutee G industrielle </option>;
    <option value='4'> 1 ann&eacutee Automatique </option>;
    <option value='5'> 2 ann&eacutee Automatique </option>;
    <option value='6'> 3 ann&eacutee Automatique </option>;
    <option value='7'> 1 ann&eacutee  &eacutelectrotechnique </option>;
    <option value='8'> 2 ann&eacutee  &eacutelectrotechnique </option>;
    <option value='9'> 3 ann&eacutee  &eacutelectrotechnique </option>;
</select>

<label >Choisir le semestre:</label>
<select name ="ssem" id="ssem">
    <option value="">--Veuillez choisir un semestre--</option>
   

    <option value='1'> S1 </option>;   
    <option value='2'> S2 </option>;
    <option value='3'> S3 </option>;
    <option value='4'> S4 </option>;
    
</select>
<input type="hidden" name="idmod"   ><br>

<button type="submit" >Valider</button>

</form>
 
  <?php 
          }   
       else {
          header("Location: premier.php?error=pas de module !!!!!");  
       } 
      ?>









     <a href="logout.php">Logout</a>



<?php 

}else{

     header("Location: premier.php");

     exit();

}

 ?>
<!--
<script type="text/javascript">

$(document).ready(function () {

$("#smod").on('change', function () {

            var id = document.getElementById("smod").value;
            alert(id);

            $("#idmod").val($$("#smod option:selected").text());
        });


     }); 
    </script>
!-->
</body>

</html>