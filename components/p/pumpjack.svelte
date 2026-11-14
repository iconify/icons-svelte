<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w_x299bxb"/><path class="e5cehub1r"/><path class="i_fi9xb3v"/><path class="mfs2uub9i"/><path class="x1e7ivbes"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pumpjack" {...props}></Icon>
<style>
:global(.e5cehub1r) {
  fill: currentColor;
  d: path("M16.5 4c2.75 0 5 2.5 5 5.5h-2.25c0-1.5-1-1.75-2.75-1.75Z");
}

:global(.i_fi9xb3v) {
  d: path("M11 6L8 21.5M11 6l3 15.5");
}

:global(.mfs2uub9i) {
  fill: currentColor;
  d: path("M2.5 12h4v4h-4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w_x299bxb) {
  d: path("M4.5 6h12");
}

:global(.x1e7ivbes) {
  d: path("M4.5 6v6m16-2.5V18M19 18h3v3.5h-3ZM2 21.5h20");
}

</style>
