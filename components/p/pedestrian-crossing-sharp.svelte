<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ywno-sh7h"/><path class="a7xbknbyy"/><path class="hp7g_gb9c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pedestrian-crossing-sharp" {...props}></Icon>
<style>
:global(.a7xbknbyy) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6.75h.01");
}

:global(.hp7g_gb9c) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.75v3.75l-2 3m2-3l2 3m-4.25-4.75L12 9.25l2.25 1.5M6 18.25h2m3 0h2m3 0h2");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.ywno-sh7h) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h18.5v18.5H2.75z");
}

</style>
