<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="hiwu68quc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:paiesque" {...props}></Icon>
<style>
:global(.hiwu68quc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 24h13l3.25 10l6.5-20l3.25 10h13");
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
