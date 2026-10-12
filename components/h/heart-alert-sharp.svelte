<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="c7atyebze"><mask id="SVG0lseHh3I" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="utmrllbfo"/></mask><g mask="url(#SVG0lseHh3I)" class="wil2krbkc"><path class="njma4u3xr"/><path class="ke2olacvp"/></g><path class="i4jylxb6o"/><path class="yqlytxbzn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:heart-alert-sharp" {...props}></Icon>
<style>
:global(.c7atyebze) {
  fill: none;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.i4jylxb6o) {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 14.5v3.25");
}

:global(.ke2olacvp) {
  d: path("m7.75 7.5l-1.929.252L5.65 9.8");
}

:global(.njma4u3xr) {
  d: path("M12 20.25h-.62l-.48-.4C7.6 17.1 3.25 13.6 3.25 8.9C3.25 6.2 5.3 4 7.9 4h2.371L12 6.2L13.729 4H16.1c2.6 0 4.65 2.2 4.65 4.9c0 4.7-4.35 8.2-7.65 10.95l-.48.4z");
}

:global(.py7ktqbvf) {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
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

:global(.yqlytxbzn) {
  stroke: currentColor;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 20.25h.01");
}

</style>
