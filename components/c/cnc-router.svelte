<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kwuja2bod"/><path class="br_el82oj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cnc-router" {...props}></Icon>
<style>
:global(.br_el82oj) {
  d: path("M10.5 9v4.5l1.5 5l1.5-5V9");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kwuja2bod) {
  d: path("M2.5 15h5v3.5h9V15h5v6.5h-19ZM11 2.5h2A1.5 1.5 0 0 1 14.5 4v3.5A1.5 1.5 0 0 1 13 9h-2a1.5 1.5 0 0 1-1.5-1.5V4A1.5 1.5 0 0 1 11 2.5");
}

</style>
