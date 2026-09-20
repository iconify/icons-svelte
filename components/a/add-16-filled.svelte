<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oyr0uzc7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:add-16-filled" {...props}></Icon>
<style>
:global(.oyr0uzc7o) {
  fill: currentColor;
  d: path("M8 1.75a.75.75 0 0 1 .75.75v4.75h4.75a.75.75 0 0 1 0 1.5H8.75v4.75a.75.75 0 0 1-1.5 0V8.75H2.5a.75.75 0 0 1 0-1.5h4.75V2.5A.75.75 0 0 1 8 1.75");
}

</style>
