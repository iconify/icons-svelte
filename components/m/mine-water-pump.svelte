<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ndxg_tbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mine-water-pump" {...props}></Icon>
<style>
:global(.ndxg_tbav) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5h4a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2v-8a2 2 0 0 1 2-2Zm6 4.5H16a2.5 2.5 0 0 1 2.5 2.5m-16 11q2.25-1.25 4.5 0t4.5 0t4.5 0t4.5 0m-2-8.25l2 3a2 2 0 0 1-4 0Z");
}

</style>
