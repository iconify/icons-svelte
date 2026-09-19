<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q7t7w6buw"/><rect class="nrzi54bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:huawei-email" {...props}></Icon>
<style>
:global(.nrzi54bje) {
  width: 37px;
  height: 31px;
  x: 5.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.q7t7w6buw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 13c13.687 13.574 14.825 13.09 29 0");
}

</style>
