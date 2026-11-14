<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pkfl3r-oe"/><path class="pb3nqwbbl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:digital-noticeboard" {...props}></Icon>
<style>
:global(.pb3nqwbbl) {
  d: path("M4.75 5.75h14.5v7.5H4.75ZM6 16v5.5M18 16v5.5");
}

:global(.pkfl3r-oe) {
  d: path("M2 3h20v13H2Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
