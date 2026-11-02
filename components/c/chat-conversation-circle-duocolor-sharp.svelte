<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d-3rr5b8k"/><path class="ja7wz_ben"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-conversation-circle-duocolor-sharp" {...props}></Icon>
<style>
:global(.d-3rr5b8k) {
  stroke-opacity: 0.4;
  d: path("M18 10a5.83 5.83 0 0 1 2 8l1 3l-3-1a5.83 5.83 0 0 1-8-2");
}

:global(.ja7wz_ben) {
  d: path("M4 12a5.83 5.83 0 1 1 2 2l-3 1Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
