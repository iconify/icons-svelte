<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dlvde0_jm"/><path class="a0zmi758o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-conversation-circle-duotone" {...props}></Icon>
<style>
:global(.a0zmi758o) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 12a5.83 5.83 0 1 1 2 2l-3 1Zm14-2a5.83 5.83 0 0 1 2 8l1 3l-3-1a5.83 5.83 0 0 1-8-2");
}

:global(.dlvde0_jm) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2.913 12.1a6.831 6.831 0 0 1 10.919-7.931A6.833 6.833 0 0 1 5.9 15.087l-2.584.862a1.001 1.001 0 0 1-1.265-1.265Z");
}

:global(.ft5dv1b6b) {
  fill: none;
}

</style>
