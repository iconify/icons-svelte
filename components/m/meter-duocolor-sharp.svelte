<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ge1buubhj"/><path class="cjftzibmt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:meter-duocolor-sharp" {...props}></Icon>
<style>
:global(.cjftzibmt) {
  d: path("M3 4h18v17H3Zm5-1v1m8-1v1M6 7h12v5H6Zm4 0v5m4-5v5");
}

:global(.ge1buubhj) {
  stroke-opacity: 0.4;
  d: path("M8 17h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
