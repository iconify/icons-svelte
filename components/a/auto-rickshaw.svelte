<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="k36g29ezv"/><path class="p74spl_tp"/><circle class="azie6ymfs"/><circle class="lu5z0ybgw"/><path class="lglu3fbzb"/><path class="xvkw7xtjm"/><path class="fx4kjbcio"/><path class="wsphit1fq"/><path class="r40lwge3n"/><circle class="t3-kt1b0r"/><circle class="i_vapmbtd"/><path class="ww5flcc5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:auto-rickshaw" {...props}></Icon>
<style>
:global(.azie6ymfs) {
  cx: 5px;
  cy: 32px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

:global(.fx4kjbcio) {
  fill: var(--svg-color--3e721d, #3e721d);
  d: path("M11 33h13c1 0 2 0 2-2c0-1 1-4 3-4s5 3 5 4s0 2 1 2s1-1 1-2V19h-8c0 3-1 8-1 8s-1-1-1 1c0 .606-1 2-2 2h-1c-1 0-2-.666-2-1.672V19c0-1-2-1-2 0v9.328C19 29.334 18.262 30 17.341 30h-3.33C13 30 12 29 12 28v-9H5c0 6 5 14 6 14");
}

:global(.i_vapmbtd) {
  cx: 30px;
  cy: 32px;
  r: 2px;
  fill: var(--svg-color--99aab5, #99aab5);
}

:global(.k36g29ezv) {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M19 9h2v11h-2z");
}

:global(.lglu3fbzb) {
  fill: var(--svg-color--1e5200, #1e5200);
  d: path("M29 23h-2a2 2 0 0 0-2 2v5a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-5a2 2 0 0 0-2-2m-10 0h-2a2 2 0 0 0-2 2v5a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-5a2 2 0 0 0-2-2");
}

:global(.lu5z0ybgw) {
  cx: 5px;
  cy: 32px;
  r: 2px;
  fill: var(--svg-color--99aab5, #99aab5);
}

:global(.p74spl_tp) {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M10 9c-2 2-4 5-4 7c0 4 5 1 5 1V9z");
}

:global(.r40lwge3n) {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M12 19H5c0-1 1-3 1-3h4a1 1 0 0 0 1-1v-4s-2 0-2-2c0-.326.106-.652.25-.944C9.573 7.4 10.258 7 10.99 7H33c2 0 3 5 3 12h-8s0-8-3-8H12z");
}

:global(.t3-kt1b0r) {
  cx: 30px;
  cy: 32px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

:global(.wsphit1fq) {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M34 32c0 1 1 0 1-2c0-3-.833-5-5-5s-5 3-5 5c0 1 1 3 1 2s.667-2 4-2s4 1 4 2");
}

:global(.ww5flcc5m) {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M9 18.5v-1a.5.5 0 0 0-.5-.5H5.552C5.286 17.648 5 18.464 5 19h3.5a.5.5 0 0 0 .5-.5");
}

:global(.xvkw7xtjm) {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M2 28.377c-1.387.225-2.581-1.152-1-2.435c2-1.623 7-2.435 9-1.623S12 33 11 33s-4-5.435-9-4.623");
}

</style>
