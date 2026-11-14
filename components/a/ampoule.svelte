<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyswk4b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:ampoule" {...props}></Icon>
<style>
:global(.oyswk4b2g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 9c0 1.5-2.5 2-2.5 4.5v6a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2v-6c0-2.5-2.5-3-2.5-4.5V5.5c0-2-1.5-3-1.5-3s-1.5 1-1.5 3ZM8 15.5h8");
}

</style>
