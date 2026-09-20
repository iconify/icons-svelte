<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ys-zbgbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:molecule-16-filled" {...props}></Icon>
<style>
:global(.ys-zbgbgs) {
  fill: currentColor;
  d: path("M11 8a3 3 0 1 0-2.707-1.705l-2.34 1.17a2.5 2.5 0 1 0 .76 3.2l2.296 1.148a2 2 0 1 0 .343-.946l-2.359-1.18Q7 9.596 7 9.5c0-.463-.126-.897-.345-1.268L8.878 7.12A3 3 0 0 0 11 8");
}

</style>
