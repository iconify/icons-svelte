<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h94jf4rcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-left-16-regular" {...props}></Icon>
<style>
:global(.h94jf4rcr) {
  fill: currentColor;
  d: path("M10.354 3.146a.5.5 0 0 1 0 .708L6.207 8l4.147 4.146a.5.5 0 0 1-.708.708l-4.5-4.5a.5.5 0 0 1 0-.708l4.5-4.5a.5.5 0 0 1 .708 0");
}

</style>
