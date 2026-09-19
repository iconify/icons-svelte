<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qdjha5_1q"/><circle class="j2zwyiste"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:clevcalc" {...props}></Icon>
<style>
:global(.j2zwyiste) {
  cx: 32.7px;
  cy: 32.8px;
  r: 6.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.qdjha5_1q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4m19 10.5H37M12.1 29.1l7.6 7.5m-.1-7.5L12 36.7m3.9-25v8.5M11.6 16h8.5m9.4 15H36m-6.5 3.6H36");
}

</style>
