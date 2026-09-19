<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-qgjebdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-download-done" {...props}></Icon>
<style>
:global(.a-qgjebdn) {
  fill: currentColor;
  d: path("M20.13 5.41L18.72 4l-9.19 9.19l-4.25-4.24l-1.41 1.41l5.66 5.66zM5 18h14v2H5z");
}

</style>
