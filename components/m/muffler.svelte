<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="btp_l8qzh"/><path class="a30jequir"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:muffler" {...props}></Icon>
<style>
:global(.a30jequir) {
  d: path("M9.5 7v10m5-10v10M2.75 10h2.5m13.5 4h2.5");
}

:global(.btp_l8qzh) {
  width: 13.5px;
  height: 10px;
  x: 5.25px;
  y: 7px;
  rx: 5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
