<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j47yg1kmm"/><path class="poo2p_bsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:monitor-upload-duocolor-sharp" {...props}></Icon>
<style>
:global(.j47yg1kmm) {
  stroke-opacity: 0.4;
  d: path("m15 10l-3-3l-3 3m3-3v7");
}

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

</style>
