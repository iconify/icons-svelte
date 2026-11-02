<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl-bfwbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:forward-duotone" {...props}></Icon>
<style>
:global(.tl-bfwbcj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17 13l4-4l-4-4m4 4H5a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h8");
}

</style>
