<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="muq4vqt9j"/><rect class="j3s9ivbxi"/><path class="ecv_sqbrh"/><circle class="psz4q_bhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:junior" {...props}></Icon>
<style>
:global(.ecv_sqbrh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18 27V14.75");
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

:global(.muq4vqt9j) {
  cx: 24px;
  cy: 27px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 6px;
  ry: 6.25px;
}

:global(.psz4q_bhy) {
  cx: 25.5px;
  cy: 13.75px;
  r: 0.75px;
  fill: currentColor;
}

</style>
