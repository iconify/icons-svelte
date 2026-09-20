<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="pte1w6bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:currency-kzt-thin" {...props}></Icon>
<style>
:global(.pte1w6bwp) {
  fill: currentColor;
  d: path("M204 96a4 4 0 0 1-4 4h-68v116a4 4 0 0 1-8 0V100H56a4 4 0 0 1 0-8h144a4 4 0 0 1 4 4M56 60h144a4 4 0 0 0 0-8H56a4 4 0 0 0 0 8");
}

</style>
