<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lv5_tlb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:calendar-3-day-32-regular" {...props}></Icon>
<style>
:global(.lv5_tlb_z) {
  fill: currentColor;
  d: path("M24.5 3A4.5 4.5 0 0 1 29 7.5v17a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3zm-17 2A2.5 2.5 0 0 0 5 7.5v17A2.5 2.5 0 0 0 7.5 27h17a2.5 2.5 0 0 0 2.5-2.5v-17A2.5 2.5 0 0 0 24.5 5zM10 9a1 1 0 0 1 1 1v12a1 1 0 1 1-2 0V10a1 1 0 0 1 1-1m6 0a1 1 0 0 1 1 1v12a1 1 0 1 1-2 0V10a1 1 0 0 1 1-1m6 0a1 1 0 0 1 1 1v12a1 1 0 1 1-2 0V10a1 1 0 0 1 1-1");
}

</style>
