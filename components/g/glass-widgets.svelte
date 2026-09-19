<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="b0yg9-b-u"/><rect class="xosu26buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:glass-widgets" {...props}></Icon>
<style>
:global(.b0yg9-b-u) {
  cx: 29.5px;
  cy: 29.5px;
  r: 13px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xosu26buq) {
  width: 24px;
  height: 24px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3px;
  ry: 3px;
}

</style>
