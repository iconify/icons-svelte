<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z539tbcdd"/><path class="qty2dywgu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:energy-meter" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qty2dywgu) {
  d: path("M7.5 10a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0m4.5 0l1.5-1.5");
}

:global(.z539tbcdd) {
  d: path("M8.375 2.5h7.25A4.375 4.375 0 0 1 20 6.875v6.25a4.375 4.375 0 0 1-4.375 4.375h-7.25A4.375 4.375 0 0 1 4 13.125v-6.25A4.375 4.375 0 0 1 8.375 2.5M9 17.5v4m6-4v4");
}

</style>
