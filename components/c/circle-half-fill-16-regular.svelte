<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n4jizvbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-half-fill-16-regular" {...props}></Icon>
<style>
:global(.n4jizvbmj) {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1m0 1a6 6 0 0 0-6 6h12a6 6 0 0 0-6-6");
}

</style>
