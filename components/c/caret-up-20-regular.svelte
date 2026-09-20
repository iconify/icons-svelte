<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wy1kq8btd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:caret-up-20-regular" {...props}></Icon>
<style>
:global(.wy1kq8btd) {
  fill: currentColor;
  d: path("M5.019 12.28a1 1 0 0 0 .778 1.628h8.407a1 1 0 0 0 .778-1.628l-3.815-4.723a1.5 1.5 0 0 0-2.334 0zm9.185.628H5.797L9.61 8.186a.5.5 0 0 1 .778 0z");
}

</style>
