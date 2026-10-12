<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q0ybizbex"/><path class="pxyd8_r1u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hockey-stick" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.pxyd8_r1u) {
  d: path("m18.75 3l-9 13.5a2 2 0 0 1-1.66.9H3.75m5.5 2.45a2.75 1.35 0 1 0 5.5 0a2.75 1.35 0 1 0-5.5 0");
}

:global(.q0ybizbex) {
  d: path("m5.25 3l9 13.5a2 2 0 0 0 1.66.9h4.34");
}

</style>
