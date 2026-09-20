<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="i3_7e1pge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:check" {...props}></Icon>
<style>
:global(.i3_7e1pge) {
  fill: currentColor;
  d: path("m229.66 77.66l-128 128a8 8 0 0 1-11.32 0l-56-56a8 8 0 0 1 11.32-11.32L96 188.69L218.34 66.34a8 8 0 0 1 11.32 11.32");
}

</style>
