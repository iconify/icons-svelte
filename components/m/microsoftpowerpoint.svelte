<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ypi47wb8h"/><path class="kv_39pk3y"/><path class="u9vx4ebcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:microsoftpowerpoint" {...props}></Icon>
<style>
:global(.kv_39pk3y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 16v16a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V16a2 2 0 0 0-2-2h-16a2 2 0 0 0-2 2");
}

:global(.u9vx4ebcu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.43 34a18.5 18.5 0 1 0 0-20");
}

:global(.ypi47wb8h) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.66 29V18h3.7a3.7 3.7 0 0 1 0 7.39h-3.7");
}

</style>
