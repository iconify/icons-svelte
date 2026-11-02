<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdgb0sbup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:notebook-fill-round" {...props}></Icon>
<style>
:global(.cdgb0sbup) {
  fill: currentColor;
  d: path("M3 16V8a5 5 0 0 1 5-5h8a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 21H8a5 5 0 0 1-5-5m6 3h7a3 3 0 0 0 3-3V8a3 3 0 0 0-3-3H9Zm7-12a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm0 4a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Z");
}

</style>
