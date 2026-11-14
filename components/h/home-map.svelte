<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="djjiqhvra"/><path class="aq7i2-bnm"/><path class="x69x7f14l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:home-map" {...props}></Icon>
<style>
:global(.aq7i2-bnm) {
  d: path("M12 17.5c-3-3.5-3.5-5-3.5-6.5a3.5 3.5 0 0 1 7 0c0 1.5-.5 3-3.5 6.5m-6-14V14m12-4v10.5");
}

:global(.djjiqhvra) {
  d: path("M6 3.5h12A3.5 3.5 0 0 1 21.5 7v10a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 17V7A3.5 3.5 0 0 1 6 3.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x69x7f14l) {
  d: path("M10.75 11a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
