<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="fx2ifgb6b"/><path class="m3_fe7bgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mobile-cloner" {...props}></Icon>
<style>
:global(.fx2ifgb6b) {
  width: 20.86px;
  height: 32.16px;
  x: 7.643px;
  y: 10.34px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.m3_fe7bgy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.5 37.66h7.857a4 4 0 0 0 4-4V9.5a4 4 0 0 0-4-4H23.496a4 4 0 0 0-4 4v.841");
}

</style>
