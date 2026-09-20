<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cnlvbw57h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:dot-outline-light" {...props}></Icon>
<style>
:global(.cnlvbw57h) {
  fill: currentColor;
  d: path("M128 98a30 30 0 1 0 30 30a30 30 0 0 0-30-30m0 48a18 18 0 1 1 18-18a18 18 0 0 1-18 18");
}

</style>
