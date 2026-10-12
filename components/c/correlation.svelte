<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="t6kpym19f"/><rect class="sn0xwt2-d"/><rect class="vjq-rp2mb"/><rect class="wkpv5vbxf"/><rect class="dhm6-cbyv"/><rect class="vf5fdmjjw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:correlation" {...props}></Icon>
<style>
:global(.dhm6-cbyv) {
  width: 4.5px;
  height: 4.5px;
  x: 9.75px;
  y: 16.75px;
  rx: 1px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sn0xwt2-d) {
  width: 4.5px;
  height: 4.5px;
  x: 2.75px;
  y: 9.75px;
  rx: 1px;
}

:global(.t6kpym19f) {
  width: 4.5px;
  height: 4.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 1px;
}

:global(.vf5fdmjjw) {
  width: 4.5px;
  height: 4.5px;
  x: 16.75px;
  y: 16.75px;
  rx: 1px;
}

:global(.vjq-rp2mb) {
  width: 4.5px;
  height: 4.5px;
  x: 9.75px;
  y: 9.75px;
  rx: 1px;
}

:global(.wkpv5vbxf) {
  width: 4.5px;
  height: 4.5px;
  x: 2.75px;
  y: 16.75px;
  rx: 1px;
}

</style>
