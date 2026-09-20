<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="enslu_bhi"/><path class="aex4p0z2m"/><path class="d-cw50bwh"/><path class="u_11xry9y"/><path class="p8x8olrmk"/><path class="vzfmp7bra"/><path class="dzjfbdtqu"/><path class="ksls36zfl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:party-clean-up-duotone-thin" {...props}></Icon>
<style>
:global(.aex4p0z2m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 11h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d-cw50bwh) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m6 5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dzjfbdtqu) {
  d: path("m6 5 3 3");
}

:global(.enslu_bhi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 11v9h10v-9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ksls36zfl) {
  d: path("m18 4 3 3");
}

:global(.p8x8olrmk) {
  d: path("M7 11v9h10v-9");
}

:global(.u_11xry9y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 4 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vzfmp7bra) {
  d: path("M5 11h14");
}

</style>
