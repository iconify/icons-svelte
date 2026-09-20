<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s26k1vbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-16-regular" {...props}></Icon>
<style>
:global(.s26k1vbal) {
  fill: currentColor;
  d: path("M8 1a7 7 0 1 1 0 14A7 7 0 0 1 8 1m0 1a6 6 0 1 0 0 12A6 6 0 0 0 8 2");
}

</style>
