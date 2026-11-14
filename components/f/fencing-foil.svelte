<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w2p-oi0yp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fencing-foil" {...props}></Icon>
<style>
:global(.w2p-oi0yp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 13.75L21 3M6 15.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm.75 1.75L3.5 20.5");
}

</style>
