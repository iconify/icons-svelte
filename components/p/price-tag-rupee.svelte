<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j1857ve9t"/><path class="iuec432cz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:price-tag-rupee" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.iuec432cz) {
  d: path("M11.5 9.25c4 0 4 4.25 0 4.25L16 17");
}

:global(.j1857ve9t) {
  d: path("M9.905 4.5h6.97A2.625 2.625 0 0 1 19.5 7.125v9.75a2.625 2.625 0 0 1-2.625 2.625h-6.97a2.63 2.63 0 0 1-2.184-1.169l-3.25-4.875a2.625 2.625 0 0 1 0-2.912l3.25-4.875A2.63 2.63 0 0 1 9.905 4.5M8.25 12h.01m2.99-2.75h5.5m-5.5 2.5h5.5");
}

</style>
