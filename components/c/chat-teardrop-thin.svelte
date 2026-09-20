<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="opm38m-1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:chat-teardrop-thin" {...props}></Icon>
<style>
:global(.opm38m-1r) {
  fill: currentColor;
  d: path("M132 28a96.11 96.11 0 0 0-96 96v84a12 12 0 0 0 12 12h84a96 96 0 0 0 0-192m0 184H48a4 4 0 0 1-4-4v-84a88 88 0 1 1 88 88");
}

</style>
