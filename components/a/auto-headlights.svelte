<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opt3xszwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:auto-headlights" {...props}></Icon>
<style>
:global(.opt3xszwj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 3.5H9a6.5 6.5 0 0 0 0 13h2Zm3 2L19.5 4M14 10h2.9m2.2 0h.4M15 21.5l3-7l3 7M16.25 19h3.5");
}

</style>
