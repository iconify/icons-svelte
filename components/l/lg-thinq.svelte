<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="zl0gqyd6k"/><circle class="gvqgig9xz"/><path class="fxwccmtmv"/><path class="l08r_wb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lg-thinq" {...props}></Icon>
<style>
:global(.fxwccmtmv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.804 33.41V17.555L24 6.982l12.464 8.67");
}

:global(.gvqgig9xz) {
  cx: 39.196px;
  cy: 17.554px;
  r: 3.304px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.l08r_wb8j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.196 20.857v18.5H19.375V24.161h10.571v9.25");
}

:global(.zl0gqyd6k) {
  cx: 8.804px;
  cy: 36.714px;
  r: 3.304px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
