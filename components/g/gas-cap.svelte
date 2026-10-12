<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="nr3vuui2s"/><path class="sjqi1-x_i"/><circle class="o5__hii-l"/><path class="zkiplcnjf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:gas-cap" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nr3vuui2s) {
  width: 14px;
  height: 14px;
  x: 5px;
  y: 5px;
  rx: 3px;
}

:global(.o5__hii-l) {
  cx: 12px;
  cy: 12px;
  r: 4.5px;
}

:global(.sjqi1-x_i) {
  d: path("M5 9.5H2.75v5H5");
}

:global(.zkiplcnjf) {
  d: path("M12 10a2 2 0 1 0 0 4a2 2 0 0 0 0-4");
}

</style>
