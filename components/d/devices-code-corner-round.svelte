<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu3jj_bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:devices-code-corner-round" {...props}></Icon>
<style>
:global(.vu3jj_bmy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 6a3 3 0 0 1 6 0v4a3 3 0 0 1-6 0Zm-4-2H7a4 4 0 0 0-4 4v4a4 4 0 0 0 4 4h3m5 1l-2 2l2 2m4-4l2 2l-2 2");
}

</style>
