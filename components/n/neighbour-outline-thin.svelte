<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jeaqztjrg"/><path class="pxkh6-9_k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:neighbour-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jeaqztjrg) {
  d: path("M2 18v-6l4 -4 4 4v6Z");
}

:global(.pxkh6-9_k) {
  d: path("M14 18v-6l4 -4 4 4v6Z");
}

</style>
