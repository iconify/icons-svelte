<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="dh5nuddxy"/><circle class="khsgttbqg"/><circle class="elsmppbpr"/><circle class="oxml-db7v"/><path class="p_125obgl"/><circle class="r7_5pvlsu"/><path class="iw25jkbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pcstartshutdown" {...props}></Icon>
<style>
:global(.dh5nuddxy) {
  cx: 14px;
  cy: 14px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.elsmppbpr) {
  cx: 14px;
  cy: 34px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.iw25jkbrp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.234 31.266a2.766 2.766 0 0 1 5.532 0a2.48 2.48 0 0 1-.81 1.955c-.573.46-1.966 1.212-1.966 2.382v.377m-22.466-7.788l-.706 2.626l2.626.706");
}

:global(.khsgttbqg) {
  cx: 34px;
  cy: 14px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.oxml-db7v) {
  cx: 34px;
  cy: 34px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.p_125obgl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.5 17.5l7-7m-7 0l7 7M12 9.968a4.5 4.5 0 1 0 4 0M14 8.5V13M9.5 34a4.5 4.5 0 1 0 1.318-3.182");
}

:global(.r7_5pvlsu) {
  cx: 34px;
  cy: 38.557px;
  r: 0.75px;
  fill: currentColor;
}

</style>
