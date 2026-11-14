<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p8u760b4u"/><path class="j2kgy3tpa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mood-history" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j2kgy3tpa) {
  d: path("m7 15l4-5.5l4 3.5l4-6.5M7 15h.01M11 9.5h.01M15 13h.01M19 6.5h.01");
}

:global(.p8u760b4u) {
  d: path("M3.5 3v17.5H21");
}

</style>
