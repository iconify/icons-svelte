<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fq7shjbor"/><path class="mzp9zz-op"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:origami-outline-thin" {...props}></Icon>
<style>
:global(.fq7shjbor) {
  d: path("M3 14h18c-1 3 -4 6 -9 6s-8 -3 -9 -6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mzp9zz-op) {
  d: path("M11 11V3l8 8Z");
}

</style>
