<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gfmzk2aqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:crop-5-4" {...props}></Icon>
<style>
:global(.gfmzk2aqj) {
  fill: currentColor;
  d: path("M19 4H5c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m0 14H5V6h14z");
}

</style>
