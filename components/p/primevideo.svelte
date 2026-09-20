<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ymuzcm6sr"/><rect class="ypabh1wof"/><circle class="bo46vl0_k"/><path class="ogupycwmy"/><circle class="cpk0fnbgt"/><path class="ep8_0931t"/><path class="s9r77nbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:primevideo" {...props}></Icon>
<style>
:global(.bo46vl0_k) {
  cx: 18.007px;
  cy: 17.675px;
  r: 0.7px;
  fill: currentColor;
}

:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ep8_0931t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.28 29.406c1.113-.45 3.092-1.05 3.688-.327c.644.781-.17 2.477-.92 3.794");
}

:global(.ogupycwmy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.007 20.125v5.3m11.738-1.009a2 2 0 0 1-1.738 1.009a2 2 0 0 1-2-2v-1.3a2 2 0 0 1 2-2a2 2 0 0 1 2 2v.65h-4m-2-.65a2 2 0 0 0-2-2a2 2 0 0 0-2 2v1.3a2 2 0 0 0 2 2a2 2 0 0 0 2-2m0 2v-8");
}

:global(.s9r77nbul) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.798 29.929c1.759 1.396 6.954 3.534 12.488 3.534a17 17 0 0 0 10.167-3.08");
}

:global(.ymuzcm6sr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.993 20.125l-2 5.3l-2-5.3");
}

:global(.ypabh1wof) {
  width: 4px;
  height: 5.3px;
  x: 32.007px;
  y: 20.215px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

</style>
