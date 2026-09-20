<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k6nj2fbya"/><path class="x50q_4bdr"/><path class="ephqv81ta"/><path class="zrtfv65fm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:infinite-scroll-outline-thin" {...props}></Icon>
<style>
:global(.ephqv81ta) {
  d: path("m9.5 14 2.5 2.5 2.5 -2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.x50q_4bdr) {
  d: path("M3 10h18");
}

:global(.zrtfv65fm) {
  d: path("M9.5 18.5 12 21l2.5 -2.5");
}

</style>
