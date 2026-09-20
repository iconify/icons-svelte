<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gnp-zgb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:re-order-dots-horizontal-20-regular" {...props}></Icon>
<style>
:global(.gnp-zgb1x) {
  fill: currentColor;
  d: path("M15 7a1 1 0 1 0 2 0a1 1 0 0 0-2 0M9 7a1 1 0 1 0 2 0a1 1 0 0 0-2 0M4 8a1 1 0 1 1 0-2a1 1 0 0 1 0 2m11 5a1 1 0 1 0 2 0a1 1 0 0 0-2 0m-5 1a1 1 0 1 1 0-2a1 1 0 0 1 0 2m-7-1a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
