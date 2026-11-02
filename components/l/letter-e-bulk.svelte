<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it9b3kbdf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-e-bulk" {...props}></Icon>
<style>
:global(.it9b3kbdf) {
  fill: currentColor;
  d: path("M8 5v6h7a1 1 0 0 1 0 2H8v6h9a1 1 0 0 1 0 2H7a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h10a1 1 0 0 1 0 2Z");
}

</style>
