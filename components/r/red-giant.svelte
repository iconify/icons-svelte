<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c_0lsxb0k"/><path class="s8l_c9bns"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:red-giant" {...props}></Icon>
<style>
:global(.c_0lsxb0k) {
  d: path("M5.5 11a8 8 0 1 0 16 0a8 8 0 1 0-16 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s8l_c9bns) {
  d: path("M11.875 15.464a4.75 4.75 0 0 1-2.839-6.089M4 20.5h.01");
}

</style>
