<!DOCTYPE html>
<html lang="en">
<head>
  <title>Portfolio</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">

   <link rel="stylesheet" href="bootstrap.min.css"/>
   
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ"
      crossorigin="anonymous"/>
    <link rel="stylesheet" type="text/css" href="style.css" />

</head>
<body data-spy="scroll" data-target="#navbarResponsive">
  <div id="home">
    <!----------------Navigation Start----------------->
    <nav class="navbar navbar-expand-md navbar-dark bg-dark fixed-top">
      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarResponsive">
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navbarResponsive">
        <ul class="navbar-nav mx-auto">
          <li class="nav-item">
            <a class="nav-link" href="#home">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#service">Projects</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#contact">Contact</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="">日本語</a>
          </li>
         
        </ul>
        
      </div>
    </nav>
    <!----------------Navigation End----------------->
    <!----------------Background Start----------------->
    <div class="background">
      <img src="back.jpg" class="img-fluid">
    </div>
    <div class="heading-content text-center">
      <h5>Hello, this is Yuma Ina's</h5>
      <h1>Engineering Laboratory</h1>
    </div>

    <!----------------Background End----------------->
  </div>


  <!----------------About Start----------------->
  <div id="about" class="offset container mt-3 mb-5">
    <div class="post-heading text-center">
      <h3 class="display-4 font-weight-bold">About Me</h3>
      <hr class="w-50 mx-auto pb-5">
    </div>
    <div class="row">
      <div class="col-lg-5 col-md-6 col-12 pb-4">
        <img src="about.png" class="img-fluid">
      </div>

      <div class="col-lg-6 col-md-6 col-12">
        <p>I love programming, learning, and traveling. I have been working full-time at one of the American job search engine companies in Tokyo. Working in tech ignited my passion for coding. I am expecting to complete coding bootcamp in March 2021 and switch careers into a software engineer.</p>
        <p>Completed courses: <a href="https://www.hyperiondev.com/portfolio/31143/">https://www.hyperiondev.com/portfolio/31143/</a></p>
        <p>Skils: Python / Java / SQL / HTML / CSS / jQuery / Git / Docker</p>
      </div>
      
    </div>

  </div>

  <!----------------About End----------------->


   <!----------------Service Start----------------->
  <div id="service" class="offset container mt-3 mb-5">
    <div class="post-heading text-center">
      <h3 class="display-4 font-weight-bold">My Projects</h3>
      <hr class="w-50 mx-auto pb-5">
    </div>

    <div class="row">

      <div class="col-lg-4 col-md-5 col-12 pb-5">
        <div class="card">
        <img class="popup card-img-top" src="project1.png" alt="image">
        <div class="card-body">
          <h5 class="card-title">My Portfolio Site</h5>
          <p class="card-text">This one-page portfolio site was developed to share what I have learned through my coding journey.</p>
          <p class="card-text">Languages: HTML / CSS / Bootstrap / jQuery</p>
          <a href="https://github.com/yuma3496/portfolio_site" class="btn btn-dark">Git Hub</a>
        </div>
      </div>
      </div>
      
      <div class="col-lg-4 col-md-5 col-12 pb-5">
        <div class="card">
        <img src="project2.png" class="popup card-img-top" alt="image">
        <div class="card-body">
          <h5 class="card-title">Task Management System</h5>
          <p class="card-text">This system is designed to assist a small business in managing tasks assigned to each member of a team. This includes creating, storing, displaying and editing tasks and related information. </p>
          <p class="card-text">Languages: Python</p>
          <a href="https://github.com/yuma3496/task_management" class="btn btn-dark">Git Hub</a>
        </div>
      </div>
      </div>

      <div class="col-lg-4 col-md-5 col-12 pb-5">
        <div class="card">
        <img src="project3.png" class="popup card-img-top" alt="image">
        <div class="card-body">
          <h5 class="card-title">Project Management Software</h5>
          <p class="card-text">This software can be used for a small structural engineering firm. This allows you to manage various projects and handle information about customers, total fee, deadline, etc. in the database. An invoice is generated for the client when a project is marked as "finalized".</p>
          <p class="card-text">Languages: Java / SQL(MySQL)</p>
          <a href="https://github.com/yuma3496/projectManagementSoftware" class="btn btn-dark">Git Hub</a>
        </div>
      </div>
      </div>
    </div>
  </div>

 <!----------------Modal Start----------------->
 <div class="modal fade bd-example-modal-lg" tabindex="-1" role="dialog" aria-labelledby="myLargeModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-lg">
    <div class="modal-content">
      <img class="w-200" id="popup-img" src="" alt="image1">
  </div>
</div>
</div>

  <!----------------Modal End----------------->

  <!----------------Service End----------------->

  <!----------------Contact Start----------------->
  <div id="contact" class=" offset w-50 mx-auto mt-5 mb-5">
    <div class="post-heading text-center">
      <h3 class="display-4 font-weight-bold">Contact Me</h3>
      <hr class="w-50 mx-auto pb-5">
    </div>
    <form action="/action_page.php">
      <div class="form-group">
        <label for="email">Full Name:</label>
        <input type="text" class="form-control" id="email">
      </div>
      <div class="form-group">
        <label for="email">Email address:</label>
        <input type="email" class="form-control" id="email">
      </div>
      <div class="form-group">
        <label for="email">Your Message:</label>
        <textarea class="form-control"></textarea>
      </div>
      <button type="submit" class="btn btn-dark">Sent</button>
    </form>

  </div>
  <!----------------Contact End----------------->

  <!----------------Footer Start----------------->
  <footer class="bg-light text-center text-lg-start">
    <!-- Copyright -->
    <div class="text-center p-3" style="background-color: black;">
      <p class="text-light">© 2021 Copyright: Yuma Ina</p>
    </div>
    <!-- Copyright -->
  </footer>
  <!----------------Footer End----------------->


    <!-- jQuery / Popper.js, / Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <!----------------<Footer End----------------->
    <script>
      $(".popup").click(function() {
        var src = $(this).attr("src");
        $(".modal").modal("show");
        $("#popup-img").attr("src", src);
      });
    </script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>

</body>
</html>
