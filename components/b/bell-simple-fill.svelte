<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="jtny9nifx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:bell-simple-fill" {...props}></Icon>
<style>
:global(.jtny9nifx) {
  fill: currentColor;
  d: path("M168 224a8 8 0 0 1-8 8H96a8 8 0 1 1 0-16h64a8 8 0 0 1 8 8m53.81-48.06C216.25 166.38 208 139.33 208 104a80 80 0 1 0-160 0c0 35.34-8.26 62.38-13.81 71.94A16 16 0 0 0 48 200h160a16 16 0 0 0 13.8-24.06Z");
}

</style>
