<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jqqdk0m7p"/><path class="gz223xb0z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:esg-letters-badge" {...props}></Icon>
<style>
:global(.gz223xb0z) {
  d: path("M8.75 15.75L7.5 21.5l2.25-1.25L12 21.5l2.25-1.25l2.25 1.25l-1.25-5.75M9 12c0-3 2-5 6-5c0 3-2 5-6 5Z");
}

:global(.jqqdk0m7p) {
  d: path("M5 9.5a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
