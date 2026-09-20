<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="qqkrm3b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:prohibit-inset-fill" {...props}></Icon>
<style>
:global(.qqkrm3b5s) {
  fill: currentColor;
  d: path("M128 24a104 104 0 1 0 104 104A104.11 104.11 0 0 0 128 24m37.66 141.66a8 8 0 0 1-11.32 0l-64-64a8 8 0 0 1 11.32-11.32l64 64a8 8 0 0 1 0 11.32");
}

</style>
