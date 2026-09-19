<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zgsu3vbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-star-half" {...props}></Icon>
<style>
:global(.zgsu3vbfi) {
  fill: currentColor;
  d: path("m22 9.24l-7.19-.62L12 2L9.19 8.63L2 9.24l5.46 4.73L5.82 21L12 17.27L18.18 21l-1.63-7.03zM12 15.4V6.1l1.71 4.04l4.38.38l-3.32 2.88l1 4.28z");
}

</style>
