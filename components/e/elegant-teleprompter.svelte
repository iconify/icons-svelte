<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="a5hlqwf3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:elegant-teleprompter" {...props}></Icon>
<style>
:global(.a5hlqwf3k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.793 19.286v-7.327h7.914m22.576 16.038v7.328h-7.914");
}

:global(.jc1oydeao) {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
