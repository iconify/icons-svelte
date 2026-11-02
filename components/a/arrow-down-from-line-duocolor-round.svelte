<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hl_mejm0r"/><path class="teuvcactv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-down-from-line-duocolor-round" {...props}></Icon>
<style>
:global(.hl_mejm0r) {
  stroke-opacity: 0.4;
  d: path("M6 4h12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.teuvcactv) {
  d: path("m8 16l4 4l4-4m-4 4V8");
}

</style>
