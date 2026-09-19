<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><circle class="lptg19b6w"/><circle class="jajl57mut"/><circle class="ru2mgne8q"/><circle class="nui94n4ej"/><circle class="irhhjrbpw"/><circle class="sdwdl440x"/><circle class="scwty563m"/><circle class="ma8il27uv"/><circle class="zuw0izl-i"/><circle class="jgli9eexe"/><circle class="m2a30zyum"/><circle class="wzzq21btz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:okay" {...props}></Icon>
<style>
:global(.i9clfwm2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

:global(.irhhjrbpw) {
  cx: 9.699px;
  cy: 25.47px;
  r: 0.75px;
  fill: currentColor;
}

:global(.jajl57mut) {
  cx: 16.175px;
  cy: 18.993px;
  r: 0.75px;
  fill: currentColor;
}

:global(.jgli9eexe) {
  cx: 14.016px;
  cy: 34.105px;
  r: 0.75px;
  fill: currentColor;
}

:global(.lptg19b6w) {
  cx: 20.669px;
  cy: 14.135px;
  r: 3.336px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.m2a30zyum) {
  cx: 11.857px;
  cy: 31.946px;
  r: 0.75px;
  fill: currentColor;
}

:global(.ma8il27uv) {
  cx: 18.404px;
  cy: 38.493px;
  r: 0.75px;
  fill: currentColor;
}

:global(.nui94n4ej) {
  cx: 11.857px;
  cy: 23.311px;
  r: 0.75px;
  fill: currentColor;
}

:global(.ru2mgne8q) {
  cx: 14.016px;
  cy: 21.152px;
  r: 0.75px;
  fill: currentColor;
}

:global(.scwty563m) {
  cx: 16.175px;
  cy: 36.264px;
  r: 0.75px;
  fill: currentColor;
}

:global(.sdwdl440x) {
  cx: 7.54px;
  cy: 27.628px;
  r: 0.75px;
  fill: currentColor;
}

:global(.wzzq21btz) {
  cx: 9.699px;
  cy: 29.787px;
  r: 0.75px;
  fill: currentColor;
}

:global(.zuw0izl-i) {
  cx: 20.633px;
  cy: 40.722px;
  r: 0.75px;
  fill: currentColor;
}

</style>
