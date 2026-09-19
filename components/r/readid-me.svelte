<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="pj3zg71xn"/><path class="epvw03b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:readid-me" {...props}></Icon>
<style>
:global(.epvw03b1k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.561 16.057c4.78 0 8.67 3.889 8.67 8.669M21.89 19.581c4.317 0 7.816 3.5 7.816 7.816");
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

:global(.pj3zg71xn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.5 19.555v15.632m5.36.026V19.581h5.03c4.317 0 7.816 3.5 7.816 7.816h0c0 4.317-3.5 7.816-7.816 7.816zm7.701-22.426c6.583 0 11.939 5.356 11.939 11.939");
}

</style>
