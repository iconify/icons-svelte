<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="bakdjm70b"/><path class="pw2fqznxu"/><circle class="pufz_nyzb"/><path class="atgi03bqv"/><path class="lob53w-yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:m365-tools" {...props}></Icon>
<style>
:global(.atgi03bqv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.075 28.578L32.935 7H24");
}

:global(.bakdjm70b) {
  cx: 9px;
  cy: 30.5px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lob53w-yd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.29 23.184L28.974 31.5h-16.62");
}

:global(.pufz_nyzb) {
  cx: 39px;
  cy: 30.5px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.pw2fqznxu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33 38.722a18 17 0 0 1-18 0");
}

</style>
