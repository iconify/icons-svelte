<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ltbnoimkc"/><path class="k70fsh3cj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:head-lice" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k70fsh3cj) {
  d: path("M10.25 5.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m-1 4L6.75 8M9 12.25H6.5m2.75 2.5l-2.5 1.75m8-6.75L17.25 8M15 12.25h2.5m-2.75 2.5l2.5 1.75m-13.75 5C5 16 3 9 4.25 2.5m16.25 19C19 16 21 9 19.75 2.5");
}

:global(.ltbnoimkc) {
  d: path("M9 12.25a3 4.5 0 1 0 6 0a3 4.5 0 1 0-6 0");
}

</style>
