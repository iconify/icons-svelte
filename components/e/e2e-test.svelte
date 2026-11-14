<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yucihkeqc"/><path class="g84ozbwgl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:e2e-test" {...props}></Icon>
<style>
:global(.g84ozbwgl) {
  d: path("m8 14.75l3 2.75l5.25-5.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yucihkeqc) {
  d: path("M7.75 4h8.5a5.25 5.25 0 0 1 5.25 5.25v5.5A5.25 5.25 0 0 1 16.25 20h-8.5a5.25 5.25 0 0 1-5.25-5.25v-5.5A5.25 5.25 0 0 1 7.75 4M2.5 9h19M6 6.5h.01M9 6.5h.01");
}

</style>
