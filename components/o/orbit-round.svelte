<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z20hp9aer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:orbit-round" {...props}></Icon>
<style>
:global(.z20hp9aer) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0m10-4a8.062 8.062 0 0 1-8 12m-6-4a8.062 8.062 0 0 1 8-12m4 2a2 2 0 1 0 4 0a2 2 0 0 0-4 0M3 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
