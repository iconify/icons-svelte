<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hae7ddcce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-down-right-16-regular" {...props}></Icon>
<style>
:global(.hae7ddcce) {
  fill: currentColor;
  d: path("M7.5 13a.5.5 0 0 0 0 1h6a.5.5 0 0 0 .5-.5v-6a.5.5 0 0 0-1 0v4.793L2.854 2.146a.5.5 0 1 0-.708.708L12.293 13z");
}

</style>
