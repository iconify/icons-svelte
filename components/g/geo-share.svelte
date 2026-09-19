<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ypcc7z3_n"/><circle class="o2vvu79vg"/><circle class="n6sr35b0x"/><circle class="fezxnaccw"/><path class="jfacwzbjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:geo-share" {...props}></Icon>
<style>
:global(.fezxnaccw) {
  cx: 37.5px;
  cy: 19.513px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.jfacwzbjr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.965 23.032c-8.891 7.641-22.358 12.034-26.541 10.7");
}

:global(.n6sr35b0x) {
  cx: 35.392px;
  cy: 35.639px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.o2vvu79vg) {
  cx: 16.384px;
  cy: 10.5px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ypcc7z3_n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.893 39.206A16.5 16.5 0 0 1 22 42.5c-9.112 0-16.5-7.387-16.5-16.5a16.5 16.5 0 0 1 6.494-13.12");
}

</style>
