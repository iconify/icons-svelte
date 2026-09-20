<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e6f21pbuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-row-two-32-regular" {...props}></Icon>
<style>
:global(.e6f21pbuw) {
  fill: currentColor;
  d: path("M3 7.5A4.5 4.5 0 0 1 7.5 3h17A4.5 4.5 0 0 1 29 7.5v17a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5zM7.5 5A2.5 2.5 0 0 0 5 7.5V15h22V7.5A2.5 2.5 0 0 0 24.5 5zM27 17H5v7.5A2.5 2.5 0 0 0 7.5 27h17a2.5 2.5 0 0 0 2.5-2.5z");
}

</style>
