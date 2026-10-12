<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="y1xvo62vd"/><path class="mzjai8b6m"/><path class="hhnxadcwk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pesticide-bottle-sharp" {...props}></Icon>
<style>
:global(.hhnxadcwk) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.75 3.5h.01M20.5 6h.01M19.5 8.5h.01");
}

:global(.mzjai8b6m) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6.25H13v2.5l2.5 2.5v10h-9v-10l2-2.5Zm1 7.5l3 3m0-3l-3 3");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.y1xvo62vd) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 3h7.5l2 1.75v1.5h-9.5ZM15 6.25l1.25 2.5");
}

</style>
