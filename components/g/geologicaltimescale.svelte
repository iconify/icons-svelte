<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="jw-x3kbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:geologicaltimescale" {...props}></Icon>
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

:global(.jw-x3kbnj) {
  fill: none;
  stroke: currentColor;
  d: path("M5.5 15.809h18.547V5.5M5.5 38.85h18.547V15.809H42.5m-18.453 6.633H42.5M24.047 8.89H42.5m-37 16.842h37M24.047 38.85H42.5m-18.453-3.452H42.5");
}

</style>
