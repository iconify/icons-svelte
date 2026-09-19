<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z85w93wkc"/><path class="gkbdyvbsy"/><rect class="j3s9ivbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:outbank" {...props}></Icon>
<style>
:global(.gkbdyvbsy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M34.5 42.5c-3 0-17-4-17-13m17-24c-3 0-17 4-17 13v11");
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

:global(.z85w93wkc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  d: path("M13.5 42.5c3 0 17-4 17-13m-17-24c3 0 17 4 17 13v11");
}

</style>
