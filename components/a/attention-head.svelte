<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="q1fvssb8e"/><path class="yqrxdvbpu"/><circle class="l68k_mbjl"/><circle class="al1gt4b8j"/><circle class="v5e7dfb-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:attention-head" {...props}></Icon>
<style>
:global(.al1gt4b8j) {
  cx: 12px;
  cy: 17.25px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l68k_mbjl) {
  cx: 5px;
  cy: 17.25px;
  r: 2px;
}

:global(.q1fvssb8e) {
  cx: 12px;
  cy: 6.5px;
  r: 2.25px;
}

:global(.v5e7dfb-y) {
  cx: 19px;
  cy: 17.25px;
  r: 2px;
}

:global(.yqrxdvbpu) {
  d: path("m10.77 8.39l-4.68 7.18M12 8.75v6.5m1.23-6.86l4.68 7.18");
}

</style>
