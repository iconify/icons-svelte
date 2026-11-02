<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fngnv_hoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:headphones-fill-round" {...props}></Icon>
<style>
:global(.fngnv_hoo) {
  fill: currentColor;
  d: path("M19.957 11.156A3 3 0 0 1 22 14v3a3 3 0 0 1-3 3h-1a3 3 0 0 1-3-3v-3a3 3 0 0 1 2.918-2.999a6 6 0 0 0-11.836 0A3 3 0 0 1 9 14v3a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-3c0-1.287.824-2.433 2.043-2.844a8.003 8.003 0 0 1 15.914 0");
}

</style>
