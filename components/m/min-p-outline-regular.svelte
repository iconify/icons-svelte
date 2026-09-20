<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tr_jskylo"/><path class="ftrg70bds"/><path class="yih0nfb7c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:min-p-outline-regular" {...props}></Icon>
<style>
:global(.ftrg70bds) {
  d: path("M17 11v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tr_jskylo) {
  d: path("M7 5v12");
}

:global(.yih0nfb7c) {
  d: path("M3 14h18");
}

</style>
