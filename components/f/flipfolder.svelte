<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hytcs1blf"/><circle class="d0k-39b4d"/><circle class="djsqzxdwc"/><circle class="xxmq3m1-v"/><circle class="ca8i64b1v"/><circle class="u47ntfq3o"/><path class="p5w7w5b5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:flipfolder" {...props}></Icon>
<style>
:global(.ca8i64b1v) {
  cx: 29.886px;
  cy: 15.817px;
  r: 1.067px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

:global(.d0k-39b4d) {
  cx: 13.701px;
  cy: 15.817px;
  r: 1.067px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

:global(.djsqzxdwc) {
  cx: 19.096px;
  cy: 15.817px;
  r: 1.067px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

:global(.hytcs1blf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.87 9.058h3.258l2.372 32.73h-37l2.372-32.73h4.2m3.318 0h18.33");
}

:global(.p5w7w5b5t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.7 6.212v2.846m0 0v5.692m21.631-8.496v2.804m0 0v5.692m.429 6.404H13.115m-.001 2.135h22.647m-22.604 2.134h22.647m-22.69 2.135h22.647M12.436 32.12H36.61m-24.174 2.135H36.61M12.372 36.39h24.174m-24.174 2.135h24.174");
}

:global(.u47ntfq3o) {
  cx: 35.281px;
  cy: 15.817px;
  r: 1.067px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

:global(.xxmq3m1-v) {
  cx: 24.491px;
  cy: 15.817px;
  r: 1.067px;
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
}

</style>
