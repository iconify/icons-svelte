<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ics7z-n9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-up-16-regular" {...props}></Icon>
<style>
:global(.ics7z-n9j) {
  fill: currentColor;
  d: path("M7.5 13.5a.5.5 0 0 0 1 0V3.803l3.628 4.031a.5.5 0 0 0 .744-.668l-4.5-5a.5.5 0 0 0-.744 0l-4.5 5a.5.5 0 0 0 .744.668L7.5 3.803z");
}

</style>
