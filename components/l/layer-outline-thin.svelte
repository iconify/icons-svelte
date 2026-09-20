<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fmulrlbrn"/><path class="fmma7fifq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:layer-outline-thin" {...props}></Icon>
<style>
:global(.fmma7fifq) {
  d: path("M8 22h8");
}

:global(.fmulrlbrn) {
  d: path("m4 12 8 -8 8 8 -8 8Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
