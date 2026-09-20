<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="pgu-1xuht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:chat-teardrop-fill" {...props}></Icon>
<style>
:global(.pgu-1xuht) {
  fill: currentColor;
  d: path("M232 124a100.11 100.11 0 0 1-100 100H48a16 16 0 0 1-16-16v-84a100 100 0 0 1 200 0");
}

</style>
