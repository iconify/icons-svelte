<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ne2dj4nyb"/><path class="bwa-9sbrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:docking-station-sharp" {...props}></Icon>
<style>
:global(.bwa-9sbrs) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 18.25h.01");
}

:global(.ne2dj4nyb) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 2.75h6v10H9zm-6.25 12.5h18.5v6H2.75zm3.5 3h2m2 0h2");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
