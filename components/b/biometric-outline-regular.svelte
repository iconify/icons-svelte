<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tcbtlrbob"/><path class="i1wcr27il"/><path class="ow28lfbqg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:biometric-outline-regular" {...props}></Icon>
<style>
:global(.i1wcr27il) {
  d: path("M5 17a7 7 0 0 1 14 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ow28lfbqg) {
  d: path("M2 17a10 10 0 0 1 20 0");
}

:global(.tcbtlrbob) {
  d: path("M8 17a4 4 0 0 1 8 0");
}

</style>
