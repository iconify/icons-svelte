<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u2dv5cc5i"/><path class="n0q0gac6b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hospital-shop" {...props}></Icon>
<style>
:global(.n0q0gac6b) {
  fill: currentColor;
  d: path("M16.5 14.25h3v2.25h2.25v3H19.5v2.25h-3V19.5h-2.25v-3h2.25Z");
}

:global(.u2dv5cc5i) {
  d: path("M11.466 18.75H5c-1.1 0-1.85-.75-1.75-1.75L4 7.5h10.5l.315 3.988M6.75 7.5v-2c0-1.75 1.25-3 2.5-3s2.5 1.25 2.5 3v2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
