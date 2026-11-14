<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="onc535byd"/><path class="w6_rv_dto"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fermenter" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.onc535byd) {
  d: path("M6.5 21.5V6h11v15.5");
}

:global(.w6_rv_dto) {
  d: path("m6.5 13.5l4 4h3l4-4m-5.5 4V20M10 6V2.5h4.5");
}

</style>
