<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qvqi41cih"/><path class="j2aic6ujd"/><path class="c3xkdj8uw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-escalate-outline-regular" {...props}></Icon>
<style>
:global(.c3xkdj8uw) {
  d: path("M14.5 5H19v4.5");
}

:global(.j2aic6ujd) {
  d: path("m12 12 7 -7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qvqi41cih) {
  d: path("M8.69 13.37a4 4 0 1 1 -3.38 0");
}

</style>
