<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o1lbe0b4b"/><path class="x8o_ol39y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bassoon" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.o1lbe0b4b) {
  d: path("M9.25 21.5L10.5 18V5.25a1.75 1.75 0 0 1 3.5 0V18l1.25 3.5Z");
}

:global(.x8o_ol39y) {
  d: path("M10.5 9C7.5 9 6 7.5 6 5L4.5 2.5");
}

</style>
