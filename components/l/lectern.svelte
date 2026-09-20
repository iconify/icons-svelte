<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ix7we3blc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:lectern" {...props}></Icon>
<style>
:global(.ix7we3blc) {
  fill: currentColor;
  d: path("m246.3 120.84l-40-80A15.92 15.92 0 0 0 192 32H64a15.92 15.92 0 0 0-14.3 8.84l-40 80A16 16 0 0 0 24 144h96v64H96a8 8 0 0 0 0 16h64a8 8 0 0 0 0-16h-24v-64h96a16 16 0 0 0 14.31-23.16ZM24 128l40-80h128l40 80Zm168-24a8 8 0 0 1-8 8H72a8 8 0 0 1 0-16h112a8 8 0 0 1 8 8");
}

</style>
