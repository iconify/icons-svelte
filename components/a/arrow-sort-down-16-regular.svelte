<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wqp9ccchb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-sort-down-16-regular" {...props}></Icon>
<style>
:global(.wqp9ccchb) {
  fill: currentColor;
  d: path("M7.146 13.854a.5.5 0 0 0 .708 0l3-3a.5.5 0 0 0-.708-.708L8 12.293V2.5a.5.5 0 0 0-1 0v9.793l-2.146-2.147a.5.5 0 0 0-.708.708z");
}

</style>
