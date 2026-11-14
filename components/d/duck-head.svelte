<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bbh99sbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:duck-head" {...props}></Icon>
<style>
:global(.bbh99sbyl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 13h3.5q1.5 0 1.25 1.75q-.5 2-6 1.25A7 7 0 1 1 17 13Zm-5-3.5h.01");
}

</style>
