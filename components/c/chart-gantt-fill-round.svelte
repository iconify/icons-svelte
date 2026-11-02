<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j0ds38bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-gantt-fill-round" {...props}></Icon>
<style>
:global(.j0ds38bra) {
  fill: currentColor;
  d: path("M4 4v12a3 3 0 0 0 3 3h14a1 1 0 0 1 0 2H7a5 5 0 0 1-5-5V4a1 1 0 0 1 2 0m3 3h6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m3 4h7a1 1 0 0 1 0 2h-7a1 1 0 0 1 0-2m10 4a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2Z");
}

</style>
