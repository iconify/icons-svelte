<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="c3h09xbhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:notches-fill" {...props}></Icon>
<style>
:global(.c3h09xbhl) {
  fill: currentColor;
  d: path("M200 40v152a8 8 0 0 1-8 8H40a8 8 0 0 1-5.66-13.66l152-152A8 8 0 0 1 200 40");
}

</style>
