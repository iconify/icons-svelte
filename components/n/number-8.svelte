<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ygqau6tqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:number-8" {...props}></Icon>
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

:global(.ygqau6tqw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.7 24a4 4 0 0 0-4 4h0a4 4 0 0 0 4 4h2.6a4 4 0 0 0 4-4h0a4 4 0 0 0-4-4m0 0a4 4 0 0 0 4-4h0a4 4 0 0 0-4-4h-2.6a4 4 0 0 0-4 4h0a4 4 0 0 0 4 4m0 0h2.6");
}

</style>
