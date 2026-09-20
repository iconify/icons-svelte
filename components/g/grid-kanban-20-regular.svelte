<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ch7h98w4o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:grid-kanban-20-regular" {...props}></Icon>
<style>
:global(.ch7h98w4o) {
  fill: currentColor;
  d: path("M2 3a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1zm6 0H3v2h5zM2 9a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1zm6 0H3v2h5zm-5 5a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1v-2a1 1 0 0 0-1-1zm0 1h5v2H3zm8-12a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1zm6 0h-5v2h5zm-5 5a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1V9a1 1 0 0 0-1-1zm0 1h5v2h-5z");
}

</style>
