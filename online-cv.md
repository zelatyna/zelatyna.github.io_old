<style >
.flexdisplay {
  display: flex;
}
.container {
  //position: relative;
  display: flex;
  flex-direction: column;
}

.header {
  display: flex;
}

.logo {
  width: 64px;
  height: 64px;
  display: block;
  margin-right: 10px;
}
.title {
  display:block;
}
.details {
  display: none;
  margin-top: 4px;
}
</style>


### Work experience 
{% include work.html %}

### Personal Projects
{% include projects.html %}

### Education
{% include edu.html %}

### Interest
{% include interest.html %}


<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script src="assets/js/display.js"></script>
