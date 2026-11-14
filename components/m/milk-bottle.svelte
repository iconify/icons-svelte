<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjuii0brc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:milk-bottle" {...props}></Icon>
<style>
:global(.gjuii0brc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 3.5h4v3c0 1.5 3 2 3 5V19a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-7.5c0-3 3-3.5 3-5ZM7 14h10");
}

</style>
