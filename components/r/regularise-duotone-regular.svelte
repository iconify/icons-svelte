<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h4xiao5dx"/><path class="be306ynmy"/><path class="iqi_aabed"/><path class="xgrfb-bqu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:regularise-duotone-regular" {...props}></Icon>
<style>
:global(.be306ynmy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h4xiao5dx) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m3 15 5 -5 5 5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iqi_aabed) {
  d: path("m3 15 5 -5 5 5 5 -5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

</style>
