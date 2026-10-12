<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mjc85m92c"/><circle class="vn5ttkwgv"/><path class="p3g8tgbqf"/><path class="lr3ddmoyz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:mouse-animal-sharp" {...props}></Icon>
<style>
:global(.lr3ddmoyz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.5 16.25l2.75.786v2.714");
}

:global(.mjc85m92c) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 15.5C4.75 12 8 9.5 12 9.5s6.75 2.75 6.75 5.75c0 1.75-1.25 3-3 3H2.15z");
}

:global(.p3g8tgbqf) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 13.5h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.vn5ttkwgv) {
  cx: 10.5px;
  cy: 8.75px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
