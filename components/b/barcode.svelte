<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="nab0ewbbo"/><rect class="srmx_jr_h"/><rect class="vf0rv0bqp"/><rect class="jc1oydeao"/><path class="mxfqalbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:barcode" {...props}></Icon>
<style>
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

:global(.mxfqalbnx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.904 12.443v23.114m11.748-23.114v23.114M32.4 12.443v23.114");
}

:global(.nab0ewbbo) {
  width: 4.327px;
  height: 23.115px;
  x: 12.615px;
  y: 12.443px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.665px;
  ry: 0.665px;
}

:global(.srmx_jr_h) {
  width: 3.616px;
  height: 23.115px;
  x: 24.718px;
  y: 12.443px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.665px;
  ry: 0.665px;
}

:global(.vf0rv0bqp) {
  width: 4.327px;
  height: 23.115px;
  x: 36.111px;
  y: 12.443px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.665px;
  ry: 0.665px;
}

</style>
