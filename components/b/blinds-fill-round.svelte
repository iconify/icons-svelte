<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="frwmx0ban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:blinds-fill-round" {...props}></Icon>
<style>
:global(.frwmx0ban) {
  fill: currentColor;
  d: path("M3 2h18a1 1 0 0 1 0 2h-1v2H4V4H3a1 1 0 0 1 0-2m17 6v2H4V8Zm0 4v1a3 3 0 0 1-3 3h-4v.171a3 3 0 1 1-2 0V16H7a3 3 0 0 1-3-3v-1Z");
}

</style>
