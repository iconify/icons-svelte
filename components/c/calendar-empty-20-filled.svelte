<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x7xhnis8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:calendar-empty-20-filled" {...props}></Icon>
<style>
:global(.x7xhnis8k) {
  fill: currentColor;
  d: path("M17 7v7.5a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 3 14.5V7zm-2.5-4A2.5 2.5 0 0 1 17 5.5V6H3v-.5A2.5 2.5 0 0 1 5.5 3z");
}

</style>
