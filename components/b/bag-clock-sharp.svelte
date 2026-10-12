<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="wil2krbkc"><path class="fo5nwek2p"/><path class="dqv2xfb4u"/></g><circle class="is-iy812x"/><path class="sob-b5brj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bag-clock-sharp" {...props}></Icon>
<style>
:global(.c7atyebze) {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.dqv2xfb4u) {
  d: path("M8.75 9.75V6.5a3.25 3.25 0 0 1 6.5 0v3.25");
}

:global(.fo5nwek2p) {
  d: path("m5.1 8.4l.094-1.643L6.84 6.75h10.32l1.646.007L18.9 8.4l.7 10.3l.051 2.551l-2.551-.001H6.9l-2.551.001L4.4 18.7Z");
}

:global(.is-iy812x) {
  cx: 17.5px;
  cy: 17.5px;
  r: 3.5px;
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

:global(.sob-b5brj) {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 15.75v1.75l1.25 1");
}

:global(.utmrllbfo) {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
  fill: var(--svg-color--000, #000);
}

:global(.wil2krbkc) {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
