<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n9kgk9_fe"/><path class="owry9q8bg"/><path class="n3c7y8oqc"/><path class="kfy179bdh"/><path class="c7hcoybli"/><path class="i1xh4tq0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:droidupnp" {...props}></Icon>
<style>
:global(.c7hcoybli) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 10.5c17.673 0 32 14.327 32 32");
}

:global(.i1xh4tq0e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 5.5c20.435 0 37 16.566 37 37m-27 0h5m6 0h5m6 0h5m-37-37v5m0 6v5m0 6v5");
}

:global(.kfy179bdh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 16.5c14.36 0 26 11.64 26 26");
}

:global(.n3c7y8oqc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 21.5c11.598 0 21 9.402 21 21");
}

:global(.n9kgk9_fe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 32.5c5.523 0 10 4.477 10 10");
}

:global(.owry9q8bg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 27.5c8.284 0 15 6.716 15 15");
}

</style>
