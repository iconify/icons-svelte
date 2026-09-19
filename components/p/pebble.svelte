<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="dvag_dbsp"/><circle class="f-zfqsbyx"/><path class="wa04nob-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pebble" {...props}></Icon>
<style>
:global(.dvag_dbsp) {
  cx: 23.822px;
  cy: 23.909px;
  r: 13.691px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.f-zfqsbyx) {
  cx: 38.488px;
  cy: 8.881px;
  r: 3.381px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wa04nob-x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.413 42.5h4.817");
}

</style>
