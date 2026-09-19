<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bfs6q6api"/><circle class="fh-pg7f6b"/><circle class="n4o_l7xur"/><circle class="or8thcb5q"/><circle class="x7hay9gex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:axmor" {...props}></Icon>
<style>
:global(.bfs6q6api) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.509 15.465l1.516 1.268a6.83 6.83 0 0 1 2.447 5.237v12.123a8.407 8.407 0 0 1-8.407 8.407h-20.13a8.407 8.407 0 0 1-8.407-8.407V22.016c0-2.048.92-3.989 2.506-5.285L19.93 7.01a6.69 6.69 0 0 1 8.522.048l6.128 5.124V6.92");
}

:global(.fh-pg7f6b) {
  cx: 20.796px;
  cy: 22.097px;
  r: 1.909px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.n4o_l7xur) {
  cx: 27.82px;
  cy: 22.097px;
  r: 1.909px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.or8thcb5q) {
  cx: 20.796px;
  cy: 29.154px;
  r: 1.909px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.x7hay9gex) {
  cx: 27.82px;
  cy: 29.154px;
  r: 1.909px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
