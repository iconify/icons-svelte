<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="g828vzbqg"/><path class="ectlz40fc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:anchor" {...props}></Icon>
<style>
:global(.ectlz40fc) {
  d: path("M12 7.25V21M8.5 10.75h7M4.75 13.5C4.75 17.75 8 21 12 21s7.25-3.25 7.25-7.5m-16 1.5l1.5-1.5l1.5 1.5m11.5 0l1.5-1.5l1.5 1.5");
}

:global(.g828vzbqg) {
  cx: 12px;
  cy: 5px;
  r: 2.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
