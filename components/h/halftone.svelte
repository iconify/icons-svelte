<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol5a60bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:halftone" {...props}></Icon>
<style>
:global(.ol5a60bjj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm11 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm8 0h.01M4 16a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm12 0h.01M6.5 21.5h.01");
}

</style>
