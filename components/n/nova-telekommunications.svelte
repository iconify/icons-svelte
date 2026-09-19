<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="hhc1tybqm"/><rect class="bhf5gigtl"/><path class="qb2etcbao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:nova-telekommunications" {...props}></Icon>
<style>
:global(.bhf5gigtl) {
  width: 5.889px;
  height: 8.889px;
  x: 18.614px;
  y: 19.555px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.944px;
  ry: 2.944px;
}

:global(.hhc1tybqm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 28.444v-8.889l5.889 8.889v-8.889");
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

:global(.qb2etcbao) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.863 19.556l-2.944 8.889l-2.945-8.889M36.525 25.5h-3.938m-.976 2.944l2.945-8.889l2.944 8.889");
}

</style>
