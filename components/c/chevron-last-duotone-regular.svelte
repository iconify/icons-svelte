<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z0s4ddcok"/><path class="eyxfr864l"/><path class="xao2ebc6f"/><path class="tb3edh0qa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevron-last-duotone-regular" {...props}></Icon>
<style>
:global(.eyxfr864l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 5 7 7 -7 7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tb3edh0qa) {
  d: path("m5 5 7 7 -7 7");
}

:global(.xao2ebc6f) {
  d: path("M21 5v14");
}

:global(.z0s4ddcok) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
