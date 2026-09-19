<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="ts6lobciv"/><path class="o06oxzfns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:papara" {...props}></Icon>
<style>
:global(.o06oxzfns) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.777 22.096v21.619");
}

:global(.ts6lobciv) {
  width: 20.429px;
  height: 27.596px;
  x: 13.777px;
  y: 4.715px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 10.214px;
  ry: 10.214px;
}

</style>
