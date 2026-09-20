<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a2mpdp7qv"/><path class="nrzizubal"/><path class="m7goar83z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cost-anomaly-outline-regular" {...props}></Icon>
<style>
:global(.a2mpdp7qv) {
  d: path("m4 7 4 -4 4 4 4 -4 4 4");
}

:global(.m7goar83z) {
  d: path("M10 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nrzizubal) {
  d: path("M7 15a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
