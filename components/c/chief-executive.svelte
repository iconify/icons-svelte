<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ohl422bke"/><path class="atv66_b1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chief-executive" {...props}></Icon>
<style>
:global(.atv66_b1j) {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ohl422bke) {
  d: path("M5.75 12a6.25 6.25 0 1 0 12.5 0a6.25 6.25 0 1 0-12.5 0ZM12 2.5v19M2.5 12h19M5.25 5.25l13.5 13.5m0-13.5l-13.5 13.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
