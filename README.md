# Beginner-Projects
<!DOCTYPE html>
<html lang="en">
<html>
<style>
  h1 {
    color: #5A514F;
  }
    p {
      color: #2D2928;
    }
  h2 {
          color: #4F525A;
  }
   h3 {
          color: #4F525A;
  }
  </style>
<head>
  <title> Hello World!</title>
</head>

<body>
  <h1> Welcome to the layout of a basic website </h1>
  <ul>
<li><a href="#Subtitles">Subtitles</a></li>
<li><a href="#Span">Span</a></li>
<li><a href="#Lists">Lists</a></li>
<li><a href="#Images&Videos">Images & Videos</a></li>
<li><a href="#LinkingtoOtherWebsites">Linking to Other Websites</a></li>
    <li><a href="#LinkingtoRelativePages">Linking to Relative Pages</a></li>
  <li><a href="#Tables">Tables</a></li>
  <li><a href="#Forms">Forms</a></li>
  </ul>

  <div>
    <p>
      To create the main heading, be sure to use the <em><strong>"h1"</em></strong> tag
    </p>

    <p>
      The <em><strong>"div"</em></strong> element separates the HTML document into sections. I personally find that it helps me add structure to my pages, and group similar elements together in one place.
    </p>
  </div>

  <div id="Subtitles">
    <p>
      The <em><strong>"id"</em></strong> element in the "div" tag helps to identify what you've grouped & where. E.g. Div <em><strong>id</em></strong>="category"
    </p>
    <h2> To create a subtitle on a document, use the <em><strong>"h#"</em></strong> tag</h2>
    <p> The head tags go from 1-6, 1 being the main title & 6 being the smallest subtitle.</p>

<div id="Span">
    <p> The <em><strong>"span"</em></strong> tag is similar to the "div" tag in that it targets specific pieces of content, however <em><strong>"span"</em></strong> is used for inline content as opposed to large blocks of text
        <p>
		To create line breaks in your HTML code, use the <em><strong>"br"</em></strong> tag. </p>
    
    <br><br>
    <p>For example, take the text "O Romeo, Romeo, wherefore art thou Romeo?"</p>
              <br><br>
<p> To create a line break, format the line in this way: "O Romeo, Romeo,<em><strong>"br"</em></strong><em><strong>"br"</em></strong> wherefore art thou Romeo?"
    </p>
</div>

<div id="Unordered Lists">
You can use an unordered list tag <em><strong>"ul"</em></strong> to create a list of items in no particular order.
<br>
You can then add individual items to the list using the <em><strong>"li"</em></strong> tag.
<br>
For example, to create a shopping list, do the following:
  <h3>Groceries</h3><p>Use the <strong>"h3"</strong> tag for this subtitle.
  To create the list, open the bracket with <strong>"ul"</strong>, then create a new line with the term <strong>"li"</strong> to describe the items.
  </p>
<ul>
  <li>Apples</li>
  <li>Oranges</li>
  <li>Pears</li>
</ul>
</div>

<div id="Lists">
  You can create an ordered list tag <em><strong>"ol"</em></strong> to create a numbered list.
<ol>
  <li> Gold </li>
  <li> Silver </li>
  <li> Bronze </li>
</ol>

</div>
<div id="Images & Videos">
  <h3> Images </h3>
 <p> To add an image, use the tag <em><strong>"img src ="</em></strong> and insert the image URL </p>
<br>
 <p> You can also use image alts to be more inclusive by adding a description of the image. This will be useful for screen reading software & non-visually impared users if the image doesn't load
  Example:
<img src="https://unsplash.com/photos/_gqq9pEVuEI alt="hot chocolate with marshmallows & gingerbread cookies decorated to look like snowflakes all on one plate on a bed">
<br>
  img src ="photo link" alt="image decription"</p>
<br>
  <p>img src does not require a closing tag</p>
<br>
<br>
<h3> Image Links </h3>
<p> Nest the <em><strong>img src="#" alt="#"</em></strong> within the a href tag:
  <br>
  <a href="https://images.unsplash.com/photo-1607686442807-c118eabfa21c?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=934&q=80" target="_blank"><img src="https://images.unsplash.com/photo-1607686442807-c118eabfa21c?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=934&q=80" width="320" height="350" alt="leaves"/></a>
  <a href="https://images.unsplash.com/photo-1607686678582-926d4a9e6f03?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=934&q=80" target="_blank"><img src="https://images.unsplash.com/photo-1607686678582-926d4a9e6f03?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=934&q=80" width="320" height="350" alt="white flowers"/></a>
  <a href="https://images.unsplash.com/photo-1607686678361-492bf032ea7d?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=934&q=80" target="_blank"><img src="https://images.unsplash.com/photo-1607686678361-492bf032ea7d?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=934&q=80" width="320" height="350" alt="leaves on vine"/></a>
</p>
<br>
<h3> Videos </h3>
  <p> Similar to the img tag, the "video" tag also requires an additional src attribute. Unlike img however, "video" does require a closing tag.</p>
<br>
  <p> After the src attribute, width & height attributes are used to set the size of the video displayed in the browser. The controls attribute instructs the browser to include basic video controls: pause, play and skip. </p>
<br>
  <p>The layout looks like this:
<br>
  video src="myVideo.mp4" width="320" height="240" controls
<br>
  /video </p>
<br>
<p> The text, “Video not supported” should be placed between the opening and closing video tags will only be displayed if the browser is unable to load the video, you must add this text in manually in between the opening and closing "video" tags</p>
</div>

<br>
<div id="LinkingtoOtherWebsites">
<h3> Linking To Other Websites </h3>
  <p> Create an anchor element <em><strong>"a"</em></strong> and attach it to a <em>href attribute</em>. This will ink to the address of the file (often a URL). The layout for this is the following:
<br>
  <strong>a href ="URL"</strong> <strong>Link description & end tag</strong>
  <a href="https://en.wikipedia.org/wiki/Zaynab_(name)"> Wikipedia definition of my name</a>
<br>
  <p> To open things in a new window, use the <em><strong>target="_blank"</em></strong> attribute at the end of the quotation marks:
<a href="https://en.wikipedia.org/wiki/Zaynab_(name)"target="_blank"> Wikipedia definition of my name that opens in a new window</a></p>

<br>
<h3> Linking To Relative Pages </h3>
<p> If you're linking to local files, the href link will look like this: <em><strong>"./File Name.html"</em></strong></p>

<br>
<div id="Tables">
<h3> Tables </h3>
<p> Start off with the <strong>table</strong> tag. Indent underneath and then use the <strong>tr</strong> tag (tr: table rows), then follow up under <em>that</em> with the <strong>td</strong> tag (td: table data) and add in the data you want to be included wihthin the cell.
<br> Now of course you'll need headings, which is where the <strong>th scope="#"</strong> tag comes in. Place this element underneath <strong>tr</strong> like this:<strong>th scope="row" (close bracket) 'Name of row' (close th tag).</strong>. Make sure this is all within the first "tr" so your rowas & columns are clearly defined. Everything after "th" is table data so the "td" tag should be used.</p>
<br><br>

<table>
<thead>
<tr>
<th scope="col"> Title of Book</th>
        <th scope="col"> Author</th>
    <th scope="col"> Would I Read Again?</th>
    </thead>
    </tr>
    
    <tbody>
    <tr>
    <td> Pachinko</td>
    <td> Min-Jin Lee</td>
    <td> Yes </td>
    </tr>
    
    <tr>
    <td> No God But God </td>
    <td> Reza Aslan </td>
    <td> No </td>
    </tr>
    
    <tr>
    <td> An American Marriage</td>
    <td> Tayari Jones</td>
    <td> Yes</td>
    </tr>
    
    <tr>
    <td colspan="3"> <strong>Barack Obama, A Promised Land </strong></td>
    <td rowspan="2"> Unfinished</td>
    </tr>
    </tbody>
    
    <tfoot>
    <td> Conclusion: read more in 2021 </td>
    </tfoot>
    </table>
    <div id="forms">
    <h3> Forms </h3>
    <p> Use the form attribute to collect information & send it elsewhere for processing: form action="'example.html" method="post". The action attribute determines where the info is sent and the method includes a verb that tells the server what to do </p>
    <p> Text input fields: If we want to create an input field in our form, we’ll need the help of the input element: input type="text/email/search/tel/url" name="..." value="pre-filled data" 
    <br>The name attribute specifies the name of a form while the value gives a pre-generated answer that tells the user what data they should input.
    
    <br>
    To create a password simply make your input type "password" and match the label & id to the label above it:
    label for="user-pw">Password: (/label>
				(input type="password" id="user-pw" name="user-pw")
        <br> To create a sliding scale on your form, use type="range" in your input element, as well as min & max attributes. Create a small step attribute too so the slider moves more smoothly: type=range min="0" max="10" step="0.5"
   <br>
   Creating a checkbox: when using the input id, include type="checkbox", and ensure that the input id & value match the label name.
   <br>
   Radio Buttons: input type="radio" id="label" name="section" value="label"
   </p>
   <br><br>
   E.g:

 <form>
    <h4> Example Form!</h4>
    <label for="username"> Username</label>
<input type="text" id="username" name="Username" placeholder="@" class="placeholder hide-on-focus">
                                                         <label for="user-pw">Password: </label>
				<input type="password" id="user-pw" name="user-pw")                                               
        <br>
        <section class="Gender">
        <span> How do you identify?</span>
          <input type="radio" id="Male" name="gender" value="Male">
          <label for="gender">Male</label>
          <input type="radio" id="Female" name="gender" value="Female">
          <label for="gender">Female</label>
          <input type="radio" id="Neither" name="gender" value="Neither">
          <label for="gender">Neither</label>
          <input type="radio" id="Prefer not to answer" name="gender" value="Prefer not to answer">
          <label for="gender">Prefer not to answer</label>
        <br>
        <section class="Contact Details">
        <span>How would you like to be contacted?</span>
        <br>
        <input id="Contact" name="`SMS" value="contact" type="checkbox">
        <label for="SMS">SMS</label>
                <input id="Contact" name="Post" value="contact" type="checkbox">
        <label for="Post">Post</label>
        <br>
                <input id="Contact" name="`Email" value="contact" type="checkbox">
        <label for="Email">Email</label>
 <input id="Contact" name="No Contact" value="contact" type="checkbox">
        <label for="No Contact">No Contact</label>
        <br>
        <section class="Where Did You Hear About Us">
        <br>
        <label for="Where Did You Hear About Us"> Where Did You Hear About Us </label>
            <select id="platforms" name="platforms">
              <option value="LinkedIn">LinkedIn</option>
              <option value="Indeed">Indeed</option>
              <option value="Target">Target</option>
              </select>
             
             <br><br>
              <label for="service">How Would You Rate Our Service?</label>
<input id="service" name="service" type="text" list="service-choices" required>
<datalist id="service-choices">
    <option value="Good"></option>
    <option value="Ok"></option>
    <option value="Terrible"></option>
    <option value="Don't Know"></option>
</datalist>
<br><br>
 <section class="extra-info">
          <label for="extra">Anything else you want to add?</label>
          <br>
					<textarea id="extra" name="extra" rows="3" cols="40"> Default text
          </textarea>
          <br>
          <section class="submission">
          <input type="Submit" value="Submit">
        </section>
</form>
</body>
</html>
