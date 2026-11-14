<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mom5-bc5j"/><path class="upv9tmqqm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fish-net" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mom5-bc5j) {
  d: path("M7 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0m2 5l-6 6");
}

:global(.upv9tmqqm) {
  d: path("M10.5 9.5C12 7 15 6.75 16.25 9.5L18 7.75v3.5L16.25 9.5C15 12.25 12 12 10.5 9.5");
}

</style>
