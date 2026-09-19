<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="lne2rnzfp"/><circle class="klh9gub9f"/><rect class="j3s9ivbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:adobe-photoshop-mix" {...props}></Icon>
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

:global(.klh9gub9f) {
  cx: 26.5px;
  cy: 26.5px;
  r: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-dasharray: 0 0 1 1.78;
  stroke-dashoffset: 1.6;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lne2rnzfp) {
  cx: 21px;
  cy: 21px;
  r: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
