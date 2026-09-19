<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="cdvrldbpt"/><path class="s7r59qb-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lineage-updater" {...props}></Icon>
<style>
:global(.cdvrldbpt) {
  width: 23.478px;
  height: 39px;
  x: 12.261px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.062px;
}

:global(.s7r59qb-r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.261 8.88h23.478M12.261 39.12h23.478M24 30V18m3.65 8.35L24 30l-3.65-3.65");
}

</style>
