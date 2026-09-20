<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="s6azad8mu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:pi" {...props}></Icon>
<style>
:global(.s6azad8mu) {
  fill: currentColor;
  d: path("M232 172a36 36 0 0 1-72 0V72H96v128a8 8 0 0 1-16 0V72h-8a40 40 0 0 0-40 40a8 8 0 0 1-16 0a56.06 56.06 0 0 1 56-56h152a8 8 0 0 1 0 16h-48v100a20 20 0 0 0 40 0a8 8 0 0 1 16 0");
}

</style>
