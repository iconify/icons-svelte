<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="j85_2wv2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:lightning-fill" {...props}></Icon>
<style>
:global(.j85_2wv2h) {
  fill: currentColor;
  d: path("m213.85 125.46l-112 120a8 8 0 0 1-13.69-7l14.66-73.33l-57.63-21.64a8 8 0 0 1-3-13l112-120a8 8 0 0 1 13.69 7l-14.7 73.41l57.63 21.61a8 8 0 0 1 3 12.95Z");
}

</style>
