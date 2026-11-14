<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xt5yb4byl"/><path class="oslqirbld"/><path class="dd-rwwsxj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:podcast-episode-download" {...props}></Icon>
<style>
:global(.dd-rwwsxj) {
  d: path("M7.348 15.652a3.75 3.75 0 1 1 5.304 0M10 14v4.75m8-4.25v7m-3-3l3 3l3-3");
}

:global(.oslqirbld) {
  d: path("M13.5 2.5v3h3M9 13a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xt5yb4byl) {
  d: path("M14.043 21.5H3.5v-19h10l3 3v6.157");
}

</style>
