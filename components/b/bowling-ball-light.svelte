<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="qut1iownw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:bowling-ball-light" {...props}></Icon>
<style>
:global(.qut1iownw) {
  fill: currentColor;
  d: path("M128 26a102 102 0 1 0 102 102A102.12 102.12 0 0 0 128 26m0 192a90 90 0 1 1 90-90a90.1 90.1 0 0 1-90 90m14-102a10 10 0 1 1-10-10a10 10 0 0 1 10 10m22-14a10 10 0 1 1 10-10a10 10 0 0 1-10 10m18 30a10 10 0 1 1-10-10a10 10 0 0 1 10 10");
}

</style>
