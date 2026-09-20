<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d67dxi68v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-circle-down-16-regular" {...props}></Icon>
<style>
:global(.d67dxi68v) {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1m0 1a6 6 0 1 0 0 12A6 6 0 0 0 8 2m2.646 4.646a.5.5 0 1 1 .707.708l-3 3a.5.5 0 0 1-.707 0l-3-3a.5.5 0 1 1 .708-.708L8 9.293z");
}

</style>
