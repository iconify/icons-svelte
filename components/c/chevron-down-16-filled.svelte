<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v4vy2dflx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-down-16-filled" {...props}></Icon>
<style>
:global(.v4vy2dflx) {
  fill: currentColor;
  d: path("M3.2 5.74a.75.75 0 0 1 1.06-.04L8 9.227L11.74 5.7a.75.75 0 1 1 1.02 1.1l-4.25 4a.75.75 0 0 1-1.02 0l-4.25-4a.75.75 0 0 1-.04-1.06");
}

</style>
