<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="wttsybcor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:provo-water" {...props}></Icon>
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

:global(.wttsybcor) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.354 18.267c-2.926 2.18-7.051 3.732-12.354-1.218s-9.427-3.398-12.354-1.218m24.708 9.387C33.428 27.398 29.303 28.949 24 24s-9.427-3.398-12.354-1.218m24.708 9.387C33.428 34.349 29.303 35.9 24 30.95s-9.427-3.398-12.354-1.218");
}

</style>
