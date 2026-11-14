<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3k84wbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:grass-clippings" {...props}></Icon>
<style>
:global(.h3k84wbmx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19C3 13 8 11 12 11s9 2 9.5 8ZM6 12.75L7.25 9M9 11.5l2-5m1 4.5l1-3m2 3.5L17.5 6");
}

</style>
