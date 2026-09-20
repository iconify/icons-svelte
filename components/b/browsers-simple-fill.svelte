<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="rzctlibej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:browsers-simple-fill" {...props}></Icon>
<style>
:global(.rzctlibej) {
  fill: currentColor;
  d: path("M200 88v112a16 16 0 0 1-16 16H40a16 16 0 0 1-16-16V88a16 16 0 0 1 16-16h144a16 16 0 0 1 16 16m16-48H64a8 8 0 0 0 0 16h152v120a8 8 0 0 0 16 0V56a16 16 0 0 0-16-16");
}

</style>
