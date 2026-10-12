<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="zs3p91b8w"/><rect class="sqimcyupq"/><rect class="s_iuhjb-d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chart" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s_iuhjb-d) {
  width: 3.25px;
  height: 11px;
  x: 16.13px;
  y: 9.25px;
  rx: 1px;
}

:global(.sqimcyupq) {
  width: 3.25px;
  height: 15.5px;
  x: 10.38px;
  y: 4.75px;
  rx: 1px;
}

:global(.zs3p91b8w) {
  width: 3.25px;
  height: 7.5px;
  x: 4.63px;
  y: 12.75px;
  rx: 1px;
}

</style>
