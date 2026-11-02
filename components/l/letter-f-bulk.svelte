<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa6pubb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-f-bulk" {...props}></Icon>
<style>
:global(.sa6pubb4r) {
  fill: currentColor;
  d: path("M8 5v6h7a1 1 0 0 1 0 2H8v7a1 1 0 0 1-2 0V4a1 1 0 0 1 1-1h10a1 1 0 0 1 0 2Z");
}

</style>
