<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="m-hzp_r0p"/><circle class="vcl8f2bsg"/><circle class="dyy5pkbxx"/><circle class="w17_uxjwj"/><path class="s9satbh8o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:git-rebase" {...props}></Icon>
<style>
:global(.dyy5pkbxx) {
  cx: 12px;
  cy: 6.75px;
  r: 2.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m-hzp_r0p) {
  cx: 5px;
  cy: 17.25px;
  r: 2.25px;
}

:global(.s9satbh8o) {
  d: path("M7.25 17.25h2.5M5 15v-3.5a4.75 4.75 0 0 1 4.75-4.75m4.5 0h1.25a3.5 3.5 0 0 1 3.5 3.5V13m-2.25-2.25L19 13l2.25-2.25");
}

:global(.vcl8f2bsg) {
  cx: 12px;
  cy: 17.25px;
  r: 2.25px;
}

:global(.w17_uxjwj) {
  cx: 19px;
  cy: 17.25px;
  r: 2.25px;
}

</style>
