<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tm--wybug"/><path class="k2uykjb4h"/><path class="d2g9hhr1o"/><path class="ub68ubbxf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:recurring-revenue" {...props}></Icon>
<style>
:global(.d2g9hhr1o) {
  d: path("M13.5 19L12 20.5l1.5 1.5m-5.75-2.639A8.5 8.5 0 0 1 12 3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k2uykjb4h) {
  d: path("M13.5 10.25q-.375-.75-1.5-.75c-.9 0-1.5.5-1.5 1.25c0 1.5 3 1 3 2.5c0 .75-.6 1.25-1.5 1.25c-.75 0-1.3-.3-1.5-.75m5.75-9.111A8.5 8.5 0 0 1 12 20.5");
}

:global(.tm--wybug) {
  d: path("M6.75 12a5.25 5.25 0 1 0 10.5 0a5.25 5.25 0 1 0-10.5 0");
}

:global(.ub68ubbxf) {
  d: path("M10.5 2L12 3.5L10.5 5");
}

</style>
