<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mpfzi8bjx"/><circle class="c_pdhbbbo"/><circle class="y81jjhz3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:oxproxion" {...props}></Icon>
<style>
:global(.c_pdhbbbo) {
  cx: 17px;
  cy: 15px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.mpfzi8bjx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17 5.5h14a9.5 9.5 0 0 1 9.5 9.5h0a9.5 9.5 0 0 1-9.5 9.5H17A9.5 9.5 0 0 1 7.5 15h0A9.5 9.5 0 0 1 17 5.5m-9.5 37V32c0-1.385 1.115-2.5 2.5-2.5h28c1.385 0 2.5 1.115 2.5 2.5v10.5z");
}

:global(.y81jjhz3d) {
  cx: 31px;
  cy: 15px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
