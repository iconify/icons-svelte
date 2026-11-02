<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycjrhkbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:desktop-tower-fill-round" {...props}></Icon>
<style>
:global(.ycjrhkbnm) {
  fill: currentColor;
  d: path("M12 8a5 5 0 0 1 10 0v8a5 5 0 0 1-9.584 2H7A5 5 0 0 1 7 8Zm5.01-1H17a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M12 16v-6H7a3 3 0 1 0 0 6Zm6 0v-3a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0m-9 3a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2Z");
}

</style>
