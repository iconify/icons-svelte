<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nsdzhhb8h"/><path class="vpuel0dtu"/><path class="bnrf8ghpe"/><path class="kycjhhb3l"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="mhnr27bap"/><path class="so0bhmbof"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:checkpoint-alert-duotone-thin" {...props}></Icon>
<style>
:global(.bnrf8ghpe) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.crv4i00bu) {
  d: path("M4 3v18");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kycjhhb3l) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 7v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lulmb9b1a) {
  d: path("M4 4h16v12H4");
}

:global(.mhnr27bap) {
  d: path("M12 7v3");
}

:global(.nsdzhhb8h) {
  fill: currentColor;
  d: path("M11 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.so0bhmbof) {
  d: path("M11 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.vpuel0dtu) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
