<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="db9b62b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-elbow-up-right" {...props}></Icon>
<style>
:global(.db9b62b4q) {
  fill: currentColor;
  d: path("m221.66 85.66l-48 48a8 8 0 0 1-11.32-11.32L196.69 88H80v136a8 8 0 0 1-16 0V80a8 8 0 0 1 8-8h124.69l-34.35-34.34a8 8 0 0 1 11.32-11.32l48 48a8 8 0 0 1 0 11.32");
}

</style>
