<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgbry6bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:celebration-star" {...props}></Icon>
<style>
:global(.kgbry6bft) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.5 4l1.91 4.371l4.747.466l-3.566 3.167l1.023 4.659L13.5 14.25l-4.114 2.413l1.023-4.659l-3.566-3.167l4.747-.466ZM3 21l3.5-3.5m-3.5-2L5.5 13");
}

</style>
