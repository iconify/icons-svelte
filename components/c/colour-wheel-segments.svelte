<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="u8lpxzb5p"/><path class="l25_b03fs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:colour-wheel-segments" {...props}></Icon>
<style>
:global(.l25_b03fs) {
  fill: currentColor;
  d: path("M12 12V2.5a9.5 9.5 0 0 1 8.25 4.75Z");
}

:global(.u8lpxzb5p) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0ZM12 2.5v19M3.75 7.25l16.5 9.5m0-9.5l-16.5 9.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
