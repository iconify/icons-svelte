<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyuq3ccod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:photo-size-select-large-outline-sharp" {...props}></Icon>
<style>
:global(.dyuq3ccod) {
  fill: currentColor;
  d: path("M3 21V7h14v14zm2-3h10l-3.4-4.5L9 17l-1.6-2.15zm14-1v-2h2v2zm0-4v-2h2v2zm0-4V7h2v2zM7 5V3h2v2zm4 0V3h2v2zm4 0V3h2v2zM3 5V3h2v2zm18 0h-2V3h2zm-2 16v-2h2v2z");
}

</style>
