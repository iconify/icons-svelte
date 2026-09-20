<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="buvqhc29l"/><path class="hl79yp-tj"/><path class="dhcdkb-uh"/><path class="j12otbcul"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:idempotent-load-outline-regular" {...props}></Icon>
<style>
:global(.buvqhc29l) {
  d: path("M2 15a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.dhcdkb-uh) {
  d: path("m18 9 -3 -3");
}

:global(.hl79yp-tj) {
  d: path("M6 4h12v5");
}

:global(.j12otbcul) {
  d: path("m8 17 3 3 5 -5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
