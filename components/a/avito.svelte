<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><circle class="szv_6cbfq"/><circle class="x8cjafb-u"/><circle class="w0ddtrcci"/><circle class="g9bakc3pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:avito" {...props}></Icon>
<style>
:global(.g9bakc3pu) {
  cx: 35.562px;
  cy: 32.878px;
  r: 6px;
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

:global(.szv_6cbfq) {
  cx: 16.602px;
  cy: 29.786px;
  r: 10.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.w0ddtrcci) {
  cx: 33.157px;
  cy: 15.853px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.x8cjafb-u) {
  cx: 18.747px;
  cy: 13.261px;
  r: 3.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
