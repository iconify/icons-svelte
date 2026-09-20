<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tixzpccws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-sort-down-16-filled" {...props}></Icon>
<style>
:global(.tixzpccws) {
  fill: currentColor;
  d: path("M7.22 13.78a.75.75 0 0 0 1.06 0l2.75-2.75a.75.75 0 1 0-1.06-1.06L8.5 11.44V2.75a.75.75 0 0 0-1.5 0v8.69L5.53 9.97a.75.75 0 0 0-1.06 1.06z");
}

</style>
