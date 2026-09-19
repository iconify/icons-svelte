<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="kd8_2gbme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:abb-mobile" {...props}></Icon>
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

:global(.kd8_2gbme) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.65 24a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4m0 0h-3.296m12.296 0a2 2 0 1 1 0 4h-3.3v-8h3.3a2 2 0 1 1 0 4m0 0h-3.296m-13.582 1.35h-3.544M12.35 28L15 20l2.65 8");
}

</style>
