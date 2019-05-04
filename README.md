<html>
<head>
	<title>Insert Biodata</title>
</head>
<body>
	<form action="contact.php" method="POST">
		<fieldset>
		<legend>Biodata</legend>
		<p>
			<label>Nama:</label>
			<input type="text" name="nama" placeholder="nama..." />
		</p>
		<p>
			<label>Address:</label>
			<input type="text" name="address" placeholder="address..."  />
		</p>
		<p>
			<label><array>Hobbies:</label></array>
			<input type="text" name="hobbies" placeholder="hobbies..."  />
		</p>
		<p>
			<label>is_married:</label>
			<input type="text" name="ismarried" placeholder="ismarried..."  />
		</p>
		<p>
			<label>School:</label>
			<label><input type="radio" name="school" value="highschool"  /> Highschool</label>
			<label><input type="radio" name="school" value="university"  /> university</label>
		</p>
		<p>
			<label>Skills:</label>
			<input type="text" name="skills" placeholder="skills..."  />
		</p>
		<p>
			<label>Biodata:</label>
			<textarea name="biodata"></textarea>
		</p>
		<p>
			<input type="submit" name="submit" value="daftar"  />
		</p>
		</fieldset>
	</form>
</body>
</html>
