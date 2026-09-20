<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i2inq9bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:dialpad-20-regular" {...props}></Icon>
<style>
:global(.i2inq9bqf) {
  fill: currentColor;
  d: path("M6 5a1 1 0 1 0 0-2a1 1 0 0 0 0 2m0 4a1 1 0 1 0 0-2a1 1 0 0 0 0 2m1 3a1 1 0 1 1-2 0a1 1 0 0 1 2 0m3-7a1 1 0 1 0 0-2a1 1 0 0 0 0 2m1 3a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-1 5a1 1 0 1 0 0-2a1 1 0 0 0 0 2m1 3a1 1 0 1 1-2 0a1 1 0 0 1 2 0m3-11a1 1 0 1 0 0-2a1 1 0 0 0 0 2m1 3a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-1 5a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
