<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="znp-i32pq"/><path class="mcihf2b2e"/><path class="cigo6d7sj"/><path class="isignkb_m"/><path class="h7k_twb0c"/><path class="crfmflbxb"/><path class="ih1xqsb_s"/><path class="xb0ugqbkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-delegate-duotone-regular" {...props}></Icon>
<style>
:global(.cigo6d7sj) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11.5 14H14v-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.crfmflbxb) {
  d: path("m10 10 2.5 2.5");
}

:global(.h7k_twb0c) {
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
}

:global(.ih1xqsb_s) {
  d: path("M11.5 14H14v-2.5");
}

:global(.isignkb_m) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19.27 15.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mcihf2b2e) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 10 2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xb0ugqbkt) {
  d: path("M19.27 15.28a3 3 0 1 1 -2.54 0");
}

:global(.znp-i32pq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.27 3.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
