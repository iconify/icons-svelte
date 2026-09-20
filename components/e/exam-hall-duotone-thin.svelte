<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hsvpncbrw"/><path class="y9xhft0uq"/><path class="okqpn0bmf"/><path class="ihsx9nb3v"/><path class="mupo5fbhr"/><path class="ehib3abci"/><path class="fhs8z1bjw"/><path class="fduloacov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:exam-hall-duotone-thin" {...props}></Icon>
<style>
:global(.ehib3abci) {
  d: path("M15 8h6v4h-6Z");
}

:global(.fduloacov) {
  d: path("M15 16h6v4h-6Z");
}

:global(.fhs8z1bjw) {
  d: path("M3 16h6v4H3Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hsvpncbrw) {
  fill: currentColor;
  d: path("M3 8h6v4H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ihsx9nb3v) {
  fill: currentColor;
  d: path("M15 16h6v4h-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.mupo5fbhr) {
  d: path("M3 8h6v4H3Z");
}

:global(.okqpn0bmf) {
  fill: currentColor;
  d: path("M3 16h6v4H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.y9xhft0uq) {
  fill: currentColor;
  d: path("M15 8h6v4h-6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
