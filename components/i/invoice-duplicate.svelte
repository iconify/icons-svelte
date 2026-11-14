<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nkjgfbcnd"/><path class="b72b2enxz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:invoice-duplicate" {...props}></Icon>
<style>
:global(.b72b2enxz) {
  d: path("M7 6.5V3h13v14.5h-4.5M7 11h5m-5 3.5h3.5");
}

:global(.nkjgfbcnd) {
  d: path("M3.5 6.5h12V21l-2-1.25l-2 1.25l-2-1.25l-2 1.25l-2-1.25l-2 1.25Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
