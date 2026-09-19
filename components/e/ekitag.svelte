<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="szynjdnbj"/><circle class="c-bmn4fhw"/><circle class="fav01bb0e"/><path class="nqv7yqb9b"/><circle class="ttbt2k9gp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ekitag" {...props}></Icon>
<style>
:global(.c-bmn4fhw) {
  cx: 35px;
  cy: 24.65px;
  r: 0.75px;
  fill: currentColor;
}

:global(.fav01bb0e) {
  cx: 36.5px;
  cy: 25.85px;
  r: 0.75px;
  fill: currentColor;
}

:global(.j3s9ivbxi) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.nqv7yqb9b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.5 5.5l-11 11");
}

:global(.szynjdnbj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.5 12.5h10m-5 0v10m-5 0h10m3-6.667h10m-10 3.334h10m-5-6.667v10m-14.667 13H22.5v-10h-10v6m16.333 4H35.5v-8m-2-2h-8v6m-13-1h10");
}

:global(.ttbt2k9gp) {
  cx: 9.085px;
  cy: 9.085px;
  r: 0.75px;
  fill: currentColor;
}

</style>
