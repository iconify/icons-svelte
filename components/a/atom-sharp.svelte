<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xf0oowkoa"/><path class="d_aj0m1-u"/><path class="agirqvbxt"/><path class="to8m3ibcr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:atom-sharp" {...props}></Icon>
<style>
:global(.agirqvbxt) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.38 20.01a9.25 3.5 120 1 0 9.25-16.02a9.25 3.5 120 1 0-9.25 16.02Z");
}

:global(.d_aj0m1-u) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.63 20.01A9.25 3.5 60 1 0 7.37 3.99a9.25 3.5 60 1 0 9.26 16.02Z");
}

:global(.to8m3ibcr) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.xf0oowkoa) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M21.25 12a9.25 3.5 0 1 0-18.5 0a9.25 3.5 0 1 0 18.5 0Z");
}

</style>
