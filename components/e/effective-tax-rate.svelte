<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="puma85-xq"/><path class="z-o_d-h1h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:effective-tax-rate" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.puma85-xq) {
  d: path("M4.5 2.5h15V21L17 19.5L14.5 21L12 19.5L9.5 21L7 19.5L4.5 21Zm11 4.5l-7 8.5");
}

:global(.z-o_d-h1h) {
  d: path("M7.5 8a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m6 6.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
