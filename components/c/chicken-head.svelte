<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x7h0d7lrj"/><path class="y1otsf-4f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chicken-head" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x7h0d7lrj) {
  d: path("M8 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0");
}

:global(.y1otsf-4f) {
  d: path("M8.25 10.5L4 12.25L8.25 14M9.5 8.5c-1-3.5 2-5 3-2.5c.5-3 4-3 4 0c1.5-1.5 4 0 1.5 3m-8.5 7.25c-2 1.25-2 4.75.5 4.5c2-.25 2.25-2.25 1.5-3.5M13 10.5h.01");
}

</style>
