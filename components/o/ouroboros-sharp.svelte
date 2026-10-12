<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="c6mzz1jyl"/><path class="im3pvtbwg"/><path class="thu-4nvfu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ouroboros-sharp" {...props}></Icon>
<style>
:global(.c6mzz1jyl) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 5.82a8 8 0 1 1-8 0l1.25 2.17a5.5 5.5 0 1 0 5.5 0Z");
}

:global(.im3pvtbwg) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.75h3.75l.73.68l1.79 1.64l.73.68l-.73.68l-1.79 1.64l-.73.68H8.5v-6z");
}

:global(.thu-4nvfu) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.25 5.75h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
