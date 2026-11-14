<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-ktqbcic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:audience-seated" {...props}></Icon>
<style>
:global(.b-ktqbcic) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.25 13h4.5v7.5h-4.5Zm7.5 0h4.5v7.5h-4.5Zm7.5 0h4.5v7.5h-4.5Zm-15-2.75v-4.5a2.25 2.25 0 0 1 4.5 0v4.5m3 0v-4.5a2.25 2.25 0 0 1 4.5 0v4.5m3 0v-4.5a2.25 2.25 0 0 1 4.5 0v4.5");
}

</style>
