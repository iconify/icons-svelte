<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="mv_rnfbza"/><circle class="n6sd4nb9d"/><circle class="zqw47pbsn"/><circle class="fnltd8uti"/><circle class="klykpxb3z"/><path class="myxslybuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:latitude" {...props}></Icon>
<style>
:global(.fnltd8uti) {
  cx: 39.081px;
  cy: 18.973px;
  r: 2.919px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.klykpxb3z) {
  cx: 39.081px;
  cy: 29.027px;
  r: 2.919px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.mv_rnfbza) {
  cx: 18.973px;
  cy: 8.919px;
  r: 2.919px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.myxslybuf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6 6v36h36v-5.838H11.838V6z");
}

:global(.n6sd4nb9d) {
  cx: 29.027px;
  cy: 8.919px;
  r: 2.919px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zqw47pbsn) {
  cx: 39.081px;
  cy: 8.919px;
  r: 2.919px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
