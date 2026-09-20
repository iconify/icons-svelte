<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="rsj49k0tj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-down-left-thin" {...props}></Icon>
<style>
:global(.rsj49k0tj) {
  fill: currentColor;
  d: path("M194.83 66.83L73.66 188H168a4 4 0 0 1 0 8H64a4 4 0 0 1-4-4V88a4 4 0 0 1 8 0v94.34L189.17 61.17a4 4 0 1 1 5.66 5.66");
}

</style>
