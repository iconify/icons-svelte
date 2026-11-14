<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m1p6lcb5o"/><path class="gjft2gz7m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:eye-mask" {...props}></Icon>
<style>
:global(.gjft2gz7m) {
  d: path("M7.75 11.5q1.5 1.5 3 0m2.5 0q1.5 1.5 3 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m1p6lcb5o) {
  d: path("M12 9c1.75-1.75 6.5-1.75 6.5 2.75c0 3.25-2.25 4.75-4.25 4c-1-.5-1.5-1.25-2.25-1.25s-1.25.75-2.25 1.25c-2 .75-4.25-.75-4.25-4c0-4.5 4.75-4.5 6.5-2.75m-9.5 2.75h3m13 0h3");
}

</style>
