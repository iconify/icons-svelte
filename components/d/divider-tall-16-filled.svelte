<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wvkn2hvcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:divider-tall-16-filled" {...props}></Icon>
<style>
:global(.wvkn2hvcj) {
  fill: currentColor;
  d: path("M7.75 1a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-1.5 0V1.75A.75.75 0 0 1 7.75 1");
}

</style>
