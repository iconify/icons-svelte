<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7ghn3b_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:crop-9-16-outline-rounded" {...props}></Icon>
<style>
:global(.u7ghn3b_b) {
  fill: currentColor;
  d: path("M9 21q-.825 0-1.412-.587T7 19V5q0-.825.588-1.412T9 3h6q.825 0 1.413.588T17 5v14q0 .825-.587 1.413T15 21zM9 5v14h6V5zm0 0v14z");
}

</style>
