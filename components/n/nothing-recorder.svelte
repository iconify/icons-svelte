<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="prx0gvbnl"/><circle class="q-7x1nbgi"/><path class="fmr-albsu"/><circle class="c0cjxbqgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nothing-recorder" {...props}></Icon>
<style>
:global(.c0cjxbqgb) {
  cx: 12.675px;
  cy: 24px;
  r: 5.223px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.fmr-albsu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.325 33.175h-22.65");
}

:global(.prx0gvbnl) {
  cx: 12.675px;
  cy: 24px;
  r: 9.175px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.q-7x1nbgi) {
  cx: 35.325px;
  cy: 24px;
  r: 9.175px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
