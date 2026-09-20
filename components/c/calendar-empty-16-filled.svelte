<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mlpqpbc9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:calendar-empty-16-filled" {...props}></Icon>
<style>
:global(.mlpqpbc9s) {
  fill: currentColor;
  d: path("M14 6v5.5a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 11.5V6zm-2.5-4A2.5 2.5 0 0 1 14 4.5V5H2v-.5A2.5 2.5 0 0 1 4.5 2z");
}

</style>
