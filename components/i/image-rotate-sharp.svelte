<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="d3kv9acig"/><path class="k5wsglbre"/><path class="m6o4r54ot"/><path class="krrr2ufus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:image-rotate-sharp" {...props}></Icon>
<style>
:global(.d3kv9acig) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 9.75h11.5v11.5H2.75z");
}

:global(.k5wsglbre) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 13.5h.01");
}

:global(.krrr2ufus) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.75 9.5L19 11.75l2.25-2.25");
}

:global(.m6o4r54ot) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.75 21.25l3.75-3.75l1-1.021l1 1.021l1.75 1.75m-2-15.5H13a6 6 0 0 1 6 6v2");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
