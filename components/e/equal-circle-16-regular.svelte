<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="metdqnihd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:equal-circle-16-regular" {...props}></Icon>
<style>
:global(.metdqnihd) {
  fill: currentColor;
  d: path("M2 8a6 6 0 1 1 12 0A6 6 0 0 1 2 8m6-7a7 7 0 1 0 0 14A7 7 0 0 0 8 1M4.5 6.5A.5.5 0 0 1 5 6h6a.5.5 0 0 1 0 1H5a.5.5 0 0 1-.5-.5m0 3A.5.5 0 0 1 5 9h6a.5.5 0 0 1 0 1H5a.5.5 0 0 1-.5-.5");
}

</style>
