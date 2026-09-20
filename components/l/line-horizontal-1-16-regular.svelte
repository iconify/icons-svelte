<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c_cq2lbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-1-16-regular" {...props}></Icon>
<style>
:global(.c_cq2lbig) {
  fill: currentColor;
  d: path("M2 7.5a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5");
}

</style>
