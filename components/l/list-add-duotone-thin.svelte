<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w95bfobed"/><path class="uzf676bdq"/><path class="cw0e2h_ie"/><path class="lb5oc-09u"/><path class="o7gb3jb7q"/><path class="nrqy16b7j"/><path class="qnmmmsbha"/><path class="ldkstzszf"/><path class="l-utwubka"/><path class="jk6bn7bej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:list-add-duotone-thin" {...props}></Icon>
<style>
:global(.cw0e2h_ie) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 16h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jk6bn7bej) {
  d: path("M15.5 12h6");
}

:global(.l-utwubka) {
  d: path("M18.5 9v6");
}

:global(.lb5oc-09u) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18.5 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ldkstzszf) {
  d: path("M3 16h11");
}

:global(.nrqy16b7j) {
  d: path("M3 6h11");
}

:global(.o7gb3jb7q) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15.5 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qnmmmsbha) {
  d: path("M3 11h11");
}

:global(.uzf676bdq) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w95bfobed) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 6h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
