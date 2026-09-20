<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="khjwrbh-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:gender-neuter" {...props}></Icon>
<style>
:global(.khjwrbh-j) {
  fill: currentColor;
  d: path("M208 104a80 80 0 1 0-88 79.6V232a8 8 0 0 0 16 0v-48.4a80.11 80.11 0 0 0 72-79.6m-80 64a64 64 0 1 1 64-64a64.07 64.07 0 0 1-64 64");
}

</style>
