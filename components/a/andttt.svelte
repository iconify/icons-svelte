<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="akpjedbrj"/><circle class="wf9okgbgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:andttt" {...props}></Icon>
<style>
:global(.akpjedbrj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24h37M24.001 5.5v37m3.756-33.13l11.116 11.116m-11.155-.002L38.832 9.37");
}

:global(.wf9okgbgf) {
  cx: 14.36px;
  cy: 33.669px;
  r: 5.715px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
