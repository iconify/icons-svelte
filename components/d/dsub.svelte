<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u9_0p7b-i"/><circle class="duohqwbdk"/><circle class="w6uopuhfn"/><path class="r5anb5bsh"/><path class="i9clfwm2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dsub" {...props}></Icon>
<style>
:global(.duohqwbdk) {
  cx: 14.352px;
  cy: 33.356px;
  r: 3.959px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.i9clfwm2k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

:global(.r5anb5bsh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24.802c4.179 0 7.755-2.565 9.25-6.205c1.47 3.62 5.071 6.205 9.25 6.205s7.755-2.565 9.25-6.205c1.495 3.64 5.071 6.205 9.25 6.205");
}

:global(.u9_0p7b-i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.311 33.356V13.892l17.254-2.391v17.898");
}

:global(.w6uopuhfn) {
  cx: 31.605px;
  cy: 29.399px;
  r: 3.959px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
