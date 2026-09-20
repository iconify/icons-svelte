<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k5ecbgu2w"/><path class="zm_si6btb"/><path class="ho2fa5bbz"/><path class="mcubrkb2y"/><path class="yqc0twwou"/><path class="wtzvy2bax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bank-reconcile-duotone-regular" {...props}></Icon>
<style>
:global(.ho2fa5bbz) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 16.5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k5ecbgu2w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mcubrkb2y) {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wtzvy2bax) {
  d: path("M8 16.5h8");
}

:global(.yqc0twwou) {
  d: path("M8 13.5h8");
}

:global(.zm_si6btb) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 13.5h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
