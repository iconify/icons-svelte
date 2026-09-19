<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zvmzeo_nw"/><rect class="i0h7071le"/><rect class="aciq_zk2j"/><rect class="rq8vzwp8r"/><rect class="wixnu8ber"/><rect class="vqdzjnbfp"/><rect class="xozcv-pcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:icon-changer" {...props}></Icon>
<style>
:global(.aciq_zk2j) {
  width: 7px;
  height: 7px;
  x: 15.5px;
  y: 10.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

:global(.i0h7071le) {
  width: 7px;
  height: 7px;
  x: 25.5px;
  y: 10.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

:global(.rq8vzwp8r) {
  width: 7px;
  height: 7px;
  x: 25.5px;
  y: 20.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

:global(.vqdzjnbfp) {
  width: 7px;
  height: 7px;
  x: 25.5px;
  y: 30.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

:global(.wixnu8ber) {
  width: 7px;
  height: 7px;
  x: 15.5px;
  y: 20.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

:global(.xozcv-pcx) {
  width: 7px;
  height: 7px;
  x: 15.5px;
  y: 30.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
  ry: 1px;
}

:global(.zvmzeo_nw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34 4.5H14a2 2 0 0 0-2 2v35a2 2 0 0 0 2 2h20a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2");
}

</style>
