<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lmxlbqbeq"/><path class="pc_0ygxgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-off-duocolor-round" {...props}></Icon>
<style>
:global(.lmxlbqbeq) {
  stroke-opacity: 0.4;
  d: path("m3 2l19 19");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pc_0ygxgn) {
  d: path("M12 17H9c-1.28 0-2.36.36-3 1l-1 1c-.738.738-2-.524-2-2V7c0-1.36.679-2.561 1.716-3.284M10 3h7a4 4 0 0 1 4 4v6q-.001.464-.101.899m-3 3q-.435.1-.899.101h-5");
}

</style>
