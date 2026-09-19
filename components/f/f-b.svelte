<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d7ehsjb3r"/><path class="n7oow16sq"/><path class="dr05ggfcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:f-b" {...props}></Icon>
<style>
:global(.d7ehsjb3r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.095 15.837h5.071v16.326h-5.071zm-3.141 2.077h3.141v12.171H6.954z");
}

:global(.dr05ggfcw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.046 30.086h-3.141V17.915h3.141zM43.5 26.65h-2.454v-5.3H43.5zm-28.334-5.137h17.668v4.973H15.166z");
}

:global(.n7oow16sq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 21.35h2.454v5.3H4.5zm33.406 10.813h-5.071V15.837h5.071z");
}

</style>
