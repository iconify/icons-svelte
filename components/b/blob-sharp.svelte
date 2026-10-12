<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ep08x_bfc"/><path class="to8m3ibcr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:blob-sharp" {...props}></Icon>
<style>
:global(.ep08x_bfc) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3c3-.25 4.5 2 6.75 2.5s3 3.5 1.75 6s-1 4.75-2.75 6.75s-5 1.5-7.25 2.25S4.75 20 4.25 17s1.25-4-.5-6.5S8.75 3.25 12 3Z");
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
