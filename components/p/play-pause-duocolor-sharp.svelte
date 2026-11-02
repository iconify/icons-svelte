<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ktr2p3bbo"/><path class="rn6ytobgk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:play-pause-duocolor-sharp" {...props}></Icon>
<style>
:global(.ktr2p3bbo) {
  stroke-opacity: 0.4;
  d: path("M17 6v12m4-12v12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rn6ytobgk) {
  d: path("m3 6l10 6l-10 6Z");
}

</style>
