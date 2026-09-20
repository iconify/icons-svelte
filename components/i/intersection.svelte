<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="u8x_ifb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:intersection" {...props}></Icon>
<style>
:global(.u8x_ifb9s) {
  fill: currentColor;
  d: path("M208 120v80a8 8 0 0 1-16 0v-80a64 64 0 0 0-128 0v80a8 8 0 0 1-16 0v-80a80 80 0 0 1 160 0");
}

</style>
