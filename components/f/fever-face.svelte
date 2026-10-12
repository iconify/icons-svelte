<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="upb39q7rv"/><path class="crn887wgg"/><circle class="l30f8ka2b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fever-face" {...props}></Icon>
<style>
:global(.crn887wgg) {
  d: path("M6.75 10.25c.6.6 1.4.6 2 0m3 0c.6.6 1.4.6 2 0m-.44 4.44L20.5 7.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l30f8ka2b) {
  cx: 12.25px;
  cy: 15.75px;
  r: 1.5px;
}

:global(.upb39q7rv) {
  cx: 10.5px;
  cy: 12.75px;
  r: 7.75px;
}

</style>
