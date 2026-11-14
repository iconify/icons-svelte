<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c85j5tb5h"/><path class="lrkmf-bnt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:e-ink-tablet" {...props}></Icon>
<style>
:global(.c85j5tb5h) {
  d: path("M9.375 2.5h5.25A4.375 4.375 0 0 1 19 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-5.25A4.375 4.375 0 0 1 5 17.125V6.875A4.375 4.375 0 0 1 9.375 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lrkmf-bnt) {
  d: path("M9.5 5.5h5A1.5 1.5 0 0 1 16 7v7a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 8 14V7a1.5 1.5 0 0 1 1.5-1.5m1 13.25h3");
}

</style>
