<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8bjzqsku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:floating-crane" {...props}></Icon>
<style>
:global(.t8bjzqsku) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 16h19l-2 4h-15ZM4 16v-4.5h5V16m-2-4.5l10.5-8m0 0v7a1.5 1.5 0 0 0 3 0");
}

</style>
