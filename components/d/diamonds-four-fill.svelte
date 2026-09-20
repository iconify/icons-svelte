<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="krbb9v7lv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:diamonds-four-fill" {...props}></Icon>
<style>
:global(.krbb9v7lv) {
  fill: currentColor;
  d: path("M82.34 69.66a8 8 0 0 1 0-11.32l40-40a8 8 0 0 1 11.32 0l40 40a8 8 0 0 1 0 11.32l-40 40a8 8 0 0 1-11.32 0Zm51.32 76.68a8 8 0 0 0-11.32 0l-40 40a8 8 0 0 0 0 11.32l40 40a8 8 0 0 0 11.32 0l40-40a8 8 0 0 0 0-11.32Zm104-24l-40-40a8 8 0 0 0-11.32 0l-40 40a8 8 0 0 0 0 11.32l40 40a8 8 0 0 0 11.32 0l40-40a8 8 0 0 0 0-11.32m-128 0l-40-40a8 8 0 0 0-11.32 0l-40 40a8 8 0 0 0 0 11.32l40 40a8 8 0 0 0 11.32 0l40-40a8 8 0 0 0 0-11.32");
}

</style>
