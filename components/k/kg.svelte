<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ef6zd4rsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kg" {...props}></Icon>
<style>
:global(.ef6zd4rsd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.5 21.426a5.05 5.05 0 0 0-5.052-5.052h0a5.05 5.05 0 0 0-5.053 5.052v5.148a5.05 5.05 0 0 0 5.053 5.052h0a5.05 5.05 0 0 0 5.052-5.052h-5.052M13.5 16.374v15.252m0-5.312l8.198-9.889m0 15.201L15.418 24");
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

</style>
