<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ezpkcccrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:calendar-3-day-32-filled" {...props}></Icon>
<style>
:global(.ezpkcccrx) {
  fill: currentColor;
  d: path("M24.5 3A4.5 4.5 0 0 1 29 7.5v17a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5v-17A4.5 4.5 0 0 1 7.5 3zM10 9a1 1 0 0 0-1 1v12a1 1 0 1 0 2 0V10a1 1 0 0 0-1-1m6 0a1 1 0 0 0-1 1v12a1 1 0 1 0 2 0V10a1 1 0 0 0-1-1m6 0a1 1 0 0 0-1 1v12a1 1 0 1 0 2 0V10a1 1 0 0 0-1-1");
}

</style>
