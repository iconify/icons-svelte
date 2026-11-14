<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5nkqtule"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bulk-bag" {...props}></Icon>
<style>
:global(.r5nkqtule) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 6.5h14c2 4 2 10 0 14H5c-2-4-2-10 0-14Zm0 0c0-4 4-4 4 0m6 0c0-4 4-4 4 0");
}

</style>
