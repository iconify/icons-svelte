<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zjps_t9lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:filter-20-filled" {...props}></Icon>
<style>
:global(.zjps_t9lz) {
  fill: currentColor;
  d: path("M12.25 13.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5zm2-4.25a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5zm2-4.25a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1 0-1.5z");
}

</style>
