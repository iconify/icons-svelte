<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ji106wfnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:open-flood" {...props}></Icon>
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

:global(.ji106wfnu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.75 5.5v37M24 5.5v37m9.25-37v37m9.25-27.75h-37m37 9.25h-37m37 9.25h-37");
}

</style>
