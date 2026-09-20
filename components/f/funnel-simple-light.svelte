<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="dojr_ibja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:funnel-simple-light" {...props}></Icon>
<style>
:global(.dojr_ibja) {
  fill: currentColor;
  d: path("M198 136a6 6 0 0 1-6 6H64a6 6 0 0 1 0-12h128a6 6 0 0 1 6 6m34-54H24a6 6 0 0 0 0 12h208a6 6 0 0 0 0-12m-80 96h-48a6 6 0 0 0 0 12h48a6 6 0 0 0 0-12");
}

</style>
