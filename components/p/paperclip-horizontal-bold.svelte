<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="dzck2fbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:paperclip-horizontal-bold" {...props}></Icon>
<style>
:global(.dzck2fbik) {
  fill: currentColor;
  d: path("M252 128a60.07 60.07 0 0 1-60 60H44a40 40 0 0 1 0-80h140a12 12 0 0 1 0 24H44a16 16 0 0 0 0 32h148a36 36 0 0 0 0-72H80a12 12 0 0 1 0-24h112a60.07 60.07 0 0 1 60 60");
}

</style>
