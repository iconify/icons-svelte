<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oaio7rbfo"/><path class="hb9j87b7j"/><circle class="vurlwubkz"/><circle class="d9a_scc5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:droplets" {...props}></Icon>
<style>
:global(.d9a_scc5e) {
  cx: 27.929px;
  cy: 24.071px;
  r: 0.75px;
  fill: currentColor;
}

:global(.hb9j87b7j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19 28a5 5 0 0 0 10 0Z");
}

:global(.oaio7rbfo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 28C8.5 14.23 24 4.5 24 4.5S39.5 14.3 39.5 28a15.5 15.5 0 0 1-31 0");
}

:global(.vurlwubkz) {
  cx: 20.098px;
  cy: 24.071px;
  r: 0.75px;
  fill: currentColor;
}

</style>
