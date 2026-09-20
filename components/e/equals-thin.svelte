<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="p86-22b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:equals-thin" {...props}></Icon>
<style>
:global(.p86-22b_l) {
  fill: currentColor;
  d: path("M220 160a4 4 0 0 1-4 4H40a4 4 0 0 1 0-8h176a4 4 0 0 1 4 4M40 100h176a4 4 0 0 0 0-8H40a4 4 0 0 0 0 8");
}

</style>
