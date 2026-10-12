<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="h-72_8bhr"/><path class="oha_9zklb"/><circle class="u_urt4jrw"/><circle class="fggvvekwy"/><circle class="aeekdrycf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:conference" {...props}></Icon>
<style>
:global(.aeekdrycf) {
  cx: 18.5px;
  cy: 18px;
  r: 2px;
}

:global(.fggvvekwy) {
  cx: 12px;
  cy: 18px;
  r: 2px;
}

:global(.h-72_8bhr) {
  width: 16.5px;
  height: 10px;
  x: 3.75px;
  y: 2.75px;
  rx: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oha_9zklb) {
  d: path("M7.75 7.75h8.5");
}

:global(.u_urt4jrw) {
  cx: 5.5px;
  cy: 18px;
  r: 2px;
}

</style>
