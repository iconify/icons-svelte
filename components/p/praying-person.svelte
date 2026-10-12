<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="eoenbp1iq"/><path class="cgisn3btn"/><path class="i9lue-apj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:praying-person" {...props}></Icon>
<style>
:global(.cgisn3btn) {
  d: path("M9.5 8.75v9h7.75a1.75 1.75 0 0 1 0 3.5H5.75");
}

:global(.eoenbp1iq) {
  cx: 9.5px;
  cy: 4.75px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i9lue-apj) {
  d: path("m9.5 10.5l3 3.25L14.75 9");
}

</style>
