<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="stu-zdbbg"/><path class="iy6c0dbab"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:irrigation-pipe-sharp" {...props}></Icon>
<style>
:global(.iy6c0dbab) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.25 20.5h.01");
}

:global(.stu-zdbbg) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13h14.5v4.5H2.75zM7 13v4.5m6-4.5v4.5M10 13V9.5m-2 0h4m5.25 5.75h3.591l.409 4.5");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
