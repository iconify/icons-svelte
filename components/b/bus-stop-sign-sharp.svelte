<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ywno-sh7h"/><path class="ku5rid9xz"/><path class="pe3q713sr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bus-stop-sign-sharp" {...props}></Icon>
<style>
:global(.ku5rid9xz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6.25h9v9.25H7V6.25zM7 11h10m-8.5 4.5v2.25m7-2.25v2.25");
}

:global(.pe3q713sr) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 13.25h.01m5.99 0h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.ywno-sh7h) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

</style>
