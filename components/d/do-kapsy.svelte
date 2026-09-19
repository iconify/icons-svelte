<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fwg_hnbzf"/><path class="et-jv6bfv"/><circle class="lfqkjcb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:do-kapsy" {...props}></Icon>
<style>
:global(.et-jv6bfv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.646 14.798c6.025 3.213 14.497 3.213 22.093-4.054M17.208 26.958c2.775-3.47 10.663-11.357 22.239-4.82");
}

:global(.fwg_hnbzf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.486 26.958V43.5H8.261v-39h23.225v2.666");
}

:global(.lfqkjcb6q) {
  cx: 26.775px;
  cy: 11.803px;
  r: 3.287px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
