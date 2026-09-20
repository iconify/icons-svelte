<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="vofztyb7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:control-light" {...props}></Icon>
<style>
:global(.vofztyb7r) {
  fill: currentColor;
  d: path("M204.24 124.24a6 6 0 0 1-8.48 0L128 56.49l-67.76 67.75a6 6 0 0 1-8.48-8.48l72-72a6 6 0 0 1 8.48 0l72 72a6 6 0 0 1 0 8.48");
}

</style>
