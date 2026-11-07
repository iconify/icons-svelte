<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhzl1ocfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:export-round" {...props}></Icon>
<style>
:global(.mhzl1ocfn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 7a2 2 0 0 0-2 2v8a4 4 0 0 0 4 4h10a4 4 0 0 0 4-4V9a2 2 0 0 0-2-2m-4-1l-3-3l-3 3m3-3v12");
}

</style>
