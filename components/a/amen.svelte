<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f880vtb4q"/><rect class="j3s9ivbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:amen" {...props}></Icon>
<style>
:global(.f880vtb4q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.88 24.692c0-1.092.884-1.977 1.976-1.977h0c1.091 0 1.976.885 1.976 1.977v3.26m-3.953-5.237v5.238m3.953-3.261c0-1.092.885-1.977 1.976-1.977h0c1.092 0 1.977.885 1.977 1.977v3.26M37 27.953v-3.261a1.976 1.976 0 0 0-1.976-1.977h0a1.976 1.976 0 0 0-1.977 1.977m0 3.261v-5.238m-1.907 4.24c-.34.596-.982.998-1.717.998h0a1.976 1.976 0 0 1-1.976-1.977v-1.284c0-1.092.885-1.976 1.976-1.976h0c1.092 0 1.976.884 1.976 1.976v.642h-3.952m-12.077 0h-3.502M11 27.952l2.619-7.905l2.618 7.905");
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
