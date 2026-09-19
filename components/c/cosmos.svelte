<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="ga-1qubuc"/><circle class="gpo8z8wkc"/><circle class="u0u_65bsx"/><circle class="vikhsj6iy"/><circle class="j4xg4js2s"/><circle class="txriz5b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cosmos" {...props}></Icon>
<style>
:global(.ga-1qubuc) {
  cx: 24px;
  cy: 9.029px;
  r: 4.081px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.gpo8z8wkc) {
  cx: 24px;
  cy: 38.867px;
  r: 4.081px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.j4xg4js2s) {
  cx: 11.08px;
  cy: 31.408px;
  r: 4.081px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.txriz5b2o) {
  cx: 36.92px;
  cy: 16.489px;
  r: 4.081px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.u0u_65bsx) {
  cx: 11.08px;
  cy: 16.489px;
  r: 4.081px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.vikhsj6iy) {
  cx: 36.92px;
  cy: 31.408px;
  r: 4.081px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
