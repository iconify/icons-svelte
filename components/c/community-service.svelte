<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gf0u97bud"/><path class="ps43subya"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:community-service" {...props}></Icon>
<style>
:global(.gf0u97bud) {
  d: path("M13.601 21H3.5V10L12 3.5l8.5 6.5v2.999M9.5 21v-5.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ps43subya) {
  d: path("m18 21.5l-3-3a2.25 2.25 0 0 1 3-2.75a2.25 2.25 0 0 1 3 2.75Z");
}

</style>
