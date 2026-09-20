<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="il0pcw8no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:pi-bold" {...props}></Icon>
<style>
:global(.il0pcw8no) {
  fill: currentColor;
  d: path("M236 172a40 40 0 0 1-80 0V76h-56v124a12 12 0 0 1-24 0V76h-4a36 36 0 0 0-36 36a12 12 0 0 1-24 0a60.07 60.07 0 0 1 60-60h152a12 12 0 0 1 0 24h-44v96a16 16 0 0 0 32 0a12 12 0 0 1 24 0");
}

</style>
