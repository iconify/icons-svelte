<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oy9aotbsd"/><path class="hvi9wjbgq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:brand-awareness" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hvi9wjbgq) {
  d: path("M7.217 9.044L8.3 7.6A1.5 1.5 0 0 1 9.5 7h5a1.5 1.5 0 0 1 1.2.6l1.083 1.444a1.5 1.5 0 0 1-.055 1.869l-3.583 4.234a1.5 1.5 0 0 1-2.29 0l-3.583-4.234a1.5 1.5 0 0 1-.055-1.869M6.5 10h11");
}

:global(.oy9aotbsd) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0");
}

</style>
