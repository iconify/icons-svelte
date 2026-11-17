<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s11dw4bis"/><path class="poo2p_bsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:monitor-code-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.poo2p_bsk) {
  d: path("M4 4h16v13H4Zm5 16h6");
}

:global(.s11dw4bis) {
  stroke-opacity: 0.4;
  d: path("m10 8.5l-2 2l2 2m4-4l2 2l-2 2");
}

</style>
