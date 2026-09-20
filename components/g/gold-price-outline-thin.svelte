<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u1klnyb3u"/><path class="rwt37ub5x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gold-price-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rwt37ub5x) {
  d: path("m5 9.5 4 -4 3 3L18.5 2");
}

:global(.u1klnyb3u) {
  d: path("m2 18.5 5 -5h10l5 5Z");
}

</style>
