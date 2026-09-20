<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="tnri-abwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:notches-bold" {...props}></Icon>
<style>
:global(.tnri-abwu) {
  fill: currentColor;
  d: path("m216.49 136.49l-80 80a12 12 0 1 1-17-17l80-80a12 12 0 1 1 17 17m-16-105a12 12 0 0 0-17 0l-152 152a12 12 0 0 0 17 17l152-152a12 12 0 0 0 0-16.98Z");
}

</style>
