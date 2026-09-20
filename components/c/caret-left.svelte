<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="i9qmm3bxu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:caret-left" {...props}></Icon>
<style>
:global(.i9qmm3bxu) {
  fill: currentColor;
  d: path("M165.66 202.34a8 8 0 0 1-11.32 11.32l-80-80a8 8 0 0 1 0-11.32l80-80a8 8 0 0 1 11.32 11.32L91.31 128Z");
}

</style>
