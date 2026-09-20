<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="km9uii_ku"/><path class="ozw9azxbj"/><path class="q9hevbcxn"/><path class="ri2m-q_tv"/><path class="jippdzaqj"/><path class="p7ecc1bwl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pipeline-retry-duotone-bold" {...props}></Icon>
<style>
:global(.jippdzaqj) {
  d: path("M8.5 14.5v-5h7v5");
}

:global(.km9uii_ku) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ozw9azxbj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8.5 14.5v-5h7v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.p7ecc1bwl) {
  d: path("m13 12 2.5 2.5L18 12");
}

:global(.q9hevbcxn) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m13 12 2.5 2.5L18 12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ri2m-q_tv) {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
