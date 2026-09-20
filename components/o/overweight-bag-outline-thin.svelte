<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="duisldofr"/><path class="zmc7aqkcp"/><path class="y5y9-x5ge"/><path class="me177l4bh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:overweight-bag-outline-thin" {...props}></Icon>
<style>
:global(.duisldofr) {
  d: path("M3 8a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.me177l4bh) {
  d: path("M11 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.y5y9-x5ge) {
  d: path("M12 11v3");
}

:global(.zmc7aqkcp) {
  d: path("M9 6V3h6v3");
}

</style>
