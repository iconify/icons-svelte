<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b1giyo3pl"/><path class="y0ru6cc5p"/><path class="pf5jncc_t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fire-hose-sign" {...props}></Icon>
<style>
:global(.b1giyo3pl) {
  d: path("M6.875 2.5h10.25A4.375 4.375 0 0 1 21.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 17.125V6.875A4.375 4.375 0 0 1 6.875 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pf5jncc_t) {
  d: path("M9.5 11a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m6 0v5.5q0 2 2 2");
}

:global(.y0ru6cc5p) {
  d: path("M6.5 11a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0");
}

</style>
