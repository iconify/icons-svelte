<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fqvaanbwm"/><path class="lwmow_bne"/><path class="a9034eb-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hydro-power-duotone-regular" {...props}></Icon>
<style>
:global(.a9034eb-p) {
  d: path("m14 8 -5 5h3l-4 4");
}

:global(.fqvaanbwm) {
  fill: currentColor;
  d: path("m12 4 8 8a8 8 0 0 1 -16 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lwmow_bne) {
  d: path("m12 4 8 8a8 8 0 0 1 -16 0Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
