<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ggrtlrbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hema" {...props}></Icon>
<style>
:global(.ggrtlrbtp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.226 27.672v-7.353l3.68 7.362l3.681-7.35v7.35M10.5 20.319v7.362m4.877-7.362v7.362M10.5 23.986h4.877m2.112.014h2.4m1.281 3.681h-3.681v-7.362h3.681m15.522 4.923h-3.261m-.808 2.439l2.439-7.362l2.438 7.362");
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
