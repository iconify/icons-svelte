<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="mjkp-82dp"/><rect class="fsx_juhum"/><path class="swtcc0ajq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:boulanger" {...props}></Icon>
<style>
:global(.fsx_juhum) {
  width: 18.306px;
  height: 13.303px;
  x: 14.847px;
  y: 18.322px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6.652px;
  ry: 6.652px;
}

:global(.mjkp-82dp) {
  width: 39px;
  height: 26.667px;
  x: 4.5px;
  y: 10.666px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 13.334px;
  ry: 13.334px;
}

:global(.swtcc0ajq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.847 24.974V11.007");
}

</style>
