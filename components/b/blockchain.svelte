<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hle17x25s"/><rect class="ee_cn_6-u"/><rect class="t9y25jb0x"/><path class="qnhcq1boi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:blockchain" {...props}></Icon>
<style>
:global(.ee_cn_6-u) {
  width: 7px;
  height: 7px;
  x: 14.25px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.hle17x25s) {
  width: 7px;
  height: 7px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qnhcq1boi) {
  d: path("M9.75 6.25h4.5m-8 3.5l3.5 4.5m8-4.5l-3.5 4.5");
}

:global(.t9y25jb0x) {
  width: 7px;
  height: 7px;
  x: 8.5px;
  y: 14.25px;
  rx: 1.5px;
}

</style>
