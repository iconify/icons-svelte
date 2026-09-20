<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dj2conhea"/><circle class="v6tf9864w"/><rect class="j3s9ivbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bns" {...props}></Icon>
<style>
:global(.dj2conhea) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.44 25.95a5.56 5.56 0 0 1 11.12 0v3.61a5.56 5.56 0 0 1-11.12 0m0 5.56V12.88");
}

:global(.j3s9ivbxi) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.v6tf9864w) {
  cx: 31.15px;
  cy: 35.12px;
  r: 0.75px;
  fill: currentColor;
}

</style>
