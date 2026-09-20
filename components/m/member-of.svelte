<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cxjcibior"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:member-of" {...props}></Icon>
<style>
:global(.cxjcibior) {
  fill: currentColor;
  d: path("M200 136H56.46A72.08 72.08 0 0 0 128 200h72a8 8 0 0 1 0 16h-72a88 88 0 0 1 0-176h72a8 8 0 0 1 0 16h-72a72.08 72.08 0 0 0-71.54 64H200a8 8 0 0 1 0 16");
}

</style>
