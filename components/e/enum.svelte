<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yo82nz7ti"/><path class="ffl91-b8z"/><path class="kfe_m-bbg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:enum" {...props}></Icon>
<style>
:global(.ffl91-b8z) {
  fill: currentColor;
  d: path("M3 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.kfe_m-bbg) {
  d: path("M3 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7-14h11m-11 7h11m-11 7h11");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yo82nz7ti) {
  d: path("M3 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

</style>
