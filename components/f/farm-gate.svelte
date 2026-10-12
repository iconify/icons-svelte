<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="uqd37fbxv"/><rect class="ch5lxybtq"/><path class="awq5oxjso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:farm-gate" {...props}></Icon>
<style>
:global(.awq5oxjso) {
  d: path("M5.5 7.5h13m-13 4h13m-13 4h13M5.5 19h13m-13 0l13-11.5");
}

:global(.ch5lxybtq) {
  width: 2.75px;
  height: 16.75px;
  x: 18.5px;
  y: 4.5px;
  rx: 0.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uqd37fbxv) {
  width: 2.75px;
  height: 16.75px;
  x: 2.75px;
  y: 4.5px;
  rx: 0.75px;
}

</style>
