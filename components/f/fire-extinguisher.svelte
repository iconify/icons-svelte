<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn7klhbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fire-extinguisher" {...props}></Icon>
<style>
:global(.jn7klhbig) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12a4 4 0 1 1 8 0v7a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2zm4-4V5l6-2M9 15h8M13 5H9a4 4 0 0 0-4 4v7");
}

</style>
