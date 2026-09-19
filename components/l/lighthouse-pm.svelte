<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="b_r7lfn8m"/><circle class="vaq46_bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lighthouse-pm" {...props}></Icon>
<style>
:global(.b_r7lfn8m) {
  width: 24px;
  height: 39px;
  x: 12px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  rx: 2px;
  ry: 2px;
}

:global(.vaq46_bqf) {
  cx: 24px;
  cy: 10px;
  r: 2px;
  fill: none;
  stroke: currentColor;
}

</style>
