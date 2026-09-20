<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hmsobbb4e"/><circle class="tt91e44vn"/><circle class="izjd51byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mydigicel" {...props}></Icon>
<style>
:global(.hmsobbb4e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.235 18.23h27.53v10.505C37.765 36.332 31.597 42.5 24 42.5s-13.765-6.168-13.765-13.765z");
}

:global(.izjd51byn) {
  cx: 33.167px;
  cy: 8.01px;
  r: 2.51px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tt91e44vn) {
  cx: 14.833px;
  cy: 8.01px;
  r: 2.51px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
