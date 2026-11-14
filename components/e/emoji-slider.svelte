<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p5g2unhun"/><path class="t3zcp6p6j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:emoji-slider" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p5g2unhun) {
  d: path("M2.5 12h3m13 0h3m-16 0a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m4.25-2h.01m4.49 0h.01");
}

:global(.t3zcp6p6j) {
  d: path("M14.815 13.625a3.25 3.25 0 0 1-5.63 0");
}

</style>
