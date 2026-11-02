<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yv8x6kb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-tree-fill" {...props}></Icon>
<style>
:global(.yv8x6kb1h) {
  fill: currentColor;
  d: path("M5 6v5h3a1 1 0 0 1 0 2H5v3a1 1 0 0 0 1 1h2a1 1 0 0 1 0 2H6a3 3 0 0 1-3-3V6a1 1 0 0 1 2 0m3-1h12a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m4 6h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2m0 6h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

</style>
