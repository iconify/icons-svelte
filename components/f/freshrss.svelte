<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e-gn2zuet"/><path class="u0v1fgb4w"/><circle class="t1mfal-np"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:freshrss" {...props}></Icon>
<style>
:global(.e-gn2zuet) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 45.5A21.5 21.5 0 1 0 2.5 24");
}

:global(.t1mfal-np) {
  cx: 24px;
  cy: 24px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.u0v1fgb4w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 39.5A15.5 15.5 0 1 0 8.5 24");
}

</style>
