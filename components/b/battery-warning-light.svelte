<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ctt6hj2tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:battery-warning-light" {...props}></Icon>
<style>
:global(.ctt6hj2tx) {
  fill: currentColor;
  d: path("M200 58H32a22 22 0 0 0-22 22v96a22 22 0 0 0 22 22h168a22 22 0 0 0 22-22V80a22 22 0 0 0-22-22m10 118a10 10 0 0 1-10 10H32a10 10 0 0 1-10-10V80a10 10 0 0 1 10-10h168a10 10 0 0 1 10 10Zm44-80v64a6 6 0 0 1-12 0V96a6 6 0 0 1 12 0m-144 28V96a6 6 0 0 1 12 0v28a6 6 0 0 1-12 0m16 32a10 10 0 1 1-10-10a10 10 0 0 1 10 10");
}

</style>
