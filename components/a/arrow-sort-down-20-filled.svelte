<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jjiicdbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-sort-down-20-filled" {...props}></Icon>
<style>
:global(.jjiicdbvr) {
  fill: currentColor;
  d: path("M9.75 17a.76.76 0 0 0 .59-.278l2.94-2.946a.75.75 0 0 0 0-1.06a.75.75 0 0 0-1.058 0L10.5 14.434V3.75a.75.75 0 0 0-1.5 0v10.694l-1.722-1.733a.75.75 0 0 0-1.059 0a.75.75 0 0 0 0 1.061l3.004 3.008a.73.73 0 0 0 .527.22");
}

</style>
