<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="er3du3bwf"/><path class="w07af_aup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:block-buster" {...props}></Icon>
<style>
:global(.er3du3bwf) {
  width: 29.514px;
  height: 29.514px;
  x: 9.38px;
  y: 9.243px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.216px;
  ry: 4.216px;
}

:global(.w07af_aup) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.662 10.477l-27.05 27.048M4.5 24.142h39");
}

</style>
