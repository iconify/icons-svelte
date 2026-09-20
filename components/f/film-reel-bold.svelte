<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="p4bfbbxqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:film-reel-bold" {...props}></Icon>
<style>
:global(.p4bfbbxqw) {
  fill: currentColor;
  d: path("M232 212h-36.2a107.94 107.94 0 1 0-67.8 24h104a12 12 0 0 0 0-24M44 128a84 84 0 1 1 84 84a84.09 84.09 0 0 1-84-84m64-44a20 20 0 1 1 20 20a20 20 0 0 1-20-20m20 108a20 20 0 1 1 20-20a20 20 0 0 1-20 20m24-64a20 20 0 1 1 20 20a20 20 0 0 1-20-20m-48 0a20 20 0 1 1-20-20a20 20 0 0 1 20 20");
}

</style>
