<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lezojdu3w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-conversation-circle" {...props}></Icon>
<style>
:global(.lezojdu3w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 12a5.83 5.83 0 1 1 2 2l-3 1Zm14-2a5.83 5.83 0 0 1 2 8l1 3l-3-1a5.83 5.83 0 0 1-8-2");
}

</style>
