<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="gbjpe-bco"/><path class="to8m3ibcr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:pillow-sharp" {...props}></Icon>
<style>
:global(.gbjpe-bco) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5C9 5 15 5 20.5 3.5C19 9 19 15 20.5 20.5C15 19 9 19 3.5 20.5C5 15 5 9 3.5 3.5Z");
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

</style>
