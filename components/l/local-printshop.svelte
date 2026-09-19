<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ka5f9uv0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:local-printshop" {...props}></Icon>
<style>
:global(.ka5f9uv0z) {
  fill: currentColor;
  d: path("M19 8H5c-1.66 0-3 1.34-3 3v6h4v4h12v-4h4v-6c0-1.66-1.34-3-3-3m-3 11H8v-5h8zm3-7c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1m-1-9H6v4h12z");
}

</style>
