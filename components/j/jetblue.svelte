<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ow8-75ftj"/><circle class="cyz18so9w"/><path class="fvldzi3zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:jetblue" {...props}></Icon>
<style>
:global(.cyz18so9w) {
  cx: 10.981px;
  cy: 19.801px;
  r: 0.75px;
  fill: currentColor;
}

:global(.fvldzi3zu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.191 25.73a1.76 1.76 0 0 1-3.288-.872v-1.143a1.76 1.76 0 1 1 3.519 0v.572h-3.519m25.903 1.443a1.76 1.76 0 0 1-3.288-.872v-1.143a1.76 1.76 0 1 1 3.519 0v.572h-3.52m-16.946-3.783v5.235c0 .485.394.88.88.88h.264m-2.067-4.663h1.847m4.73 1.144a1.76 1.76 0 0 1 0 3.518h-2.903v-7.037h2.903a1.76 1.76 0 0 1 0 3.518m0 0h-2.903m6.301-3.519v6.159c0 .485.394.88.88.88h.263m1.389-4.663v2.903a1.76 1.76 0 1 0 3.519 0v-2.903m-.001 2.903v1.759");
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

:global(.ow8-75ftj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.981 21.956v5.8c0 .66-.529 1.193-1.182 1.193c-.326 0-.621-.133-.835-.349");
}

</style>
