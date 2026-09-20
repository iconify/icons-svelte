<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="a61ohbh3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:egg-fill" {...props}></Icon>
<style>
:global(.a61ohbh3v) {
  fill: currentColor;
  d: path("M216 152a88 88 0 0 1-176 0c0-30.77 10.7-64.46 29.34-92.44C87.53 32.29 109.46 16 128 16s40.47 16.29 58.66 43.56C205.3 87.54 216 121.23 216 152");
}

</style>
