<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ny_kklbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mova" {...props}></Icon>
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

:global(.ny_kklbmp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27 24l2 5.3l4-10.6l4 10.6M11 26a2 2 0 1 1 4 0v3.3M11 24v5.3m4-3.3a2 2 0 1 1 4 0v3.3m2-3.3a2 2 0 1 1 4 0v1.3a2 2 0 1 1-4 0zm12-.94h2.4");
}

</style>
