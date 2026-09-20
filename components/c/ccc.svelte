<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="mznvk9boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ccc" {...props}></Icon>
<style>
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

:global(.mznvk9boq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.1 25.64v.041a3.3 3.3 0 1 1-6.6 0V22.32a3.3 3.3 0 1 1 6.6 0v.04m9.2 3.28v.041a3.3 3.3 0 1 1-6.6 0V22.32a3.3 3.3 0 1 1 6.6 0v.04m9.2 3.28v.041a3.3 3.3 0 1 1-6.6 0V22.32a3.3 3.3 0 1 1 6.6 0v.04");
}

</style>
