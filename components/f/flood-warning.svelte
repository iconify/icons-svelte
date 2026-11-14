<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iaonqbthp"/><path class="eirtzqbmh"/><path class="g21a8hbaa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:flood-warning" {...props}></Icon>
<style>
:global(.eirtzqbmh) {
  d: path("M10 15.75V11h4v3.25");
}

:global(.g21a8hbaa) {
  d: path("M2.5 15q2.25-1.5 4.75 0T12 15t4.75 0t4.75 0m-19 4q2.25-1.5 4.75 0T12 19t4.75 0t4.75 0");
}

:global(.iaonqbthp) {
  d: path("M4 14.25V9.5L12 3l8 6.5v6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
