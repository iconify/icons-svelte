<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="fepl4ybjy"/><path class="jm7ytx8vq"/><rect class="mugr19b-p"/><path class="uf23bpmyf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:compare-products" {...props}></Icon>
<style>
:global(.fepl4ybjy) {
  width: 7.5px;
  height: 12.75px;
  x: 2.75px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jm7ytx8vq) {
  d: path("M5 6.5h3m-3 3h3");
}

:global(.mugr19b-p) {
  width: 7.5px;
  height: 12.75px;
  x: 13.75px;
  y: 2.75px;
  rx: 1.5px;
}

:global(.uf23bpmyf) {
  d: path("M16 6.5h3m-3 3h3M5.25 19.25h13.5M7.25 17.5l-2 1.75l2 1.75m9.5-3.5l2 1.75l-2 1.75");
}

</style>
