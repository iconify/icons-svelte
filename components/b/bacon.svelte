<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jirvy6b8s"/><path class="xixzpjbkr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bacon" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jirvy6b8s) {
  d: path("M2.75 8.75c2.08-2 4.17-2 6.25 0s4.17 2 6.25 0s4-2 6 0v7q-3-3-6 0c-3 3-4.17 2-6.25 0s-4.17-2-6.25 0Z");
}

:global(.xixzpjbkr) {
  d: path("M6 11c1-.3 2 .1 3 1.15c2.08 2 4.17 2 6.25 0q1.425-1.425 2.85-1.2");
}

</style>
