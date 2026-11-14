<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ec-sy5buu"/><path class="p6ou0pbzv"/><path class="zdizkqbrb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:plant-label" {...props}></Icon>
<style>
:global(.ec-sy5buu) {
  d: path("M5.625 3h4.788a2.63 2.63 0 0 1 1.856.769l6.875 6.875a2.625 2.625 0 0 1 0 3.712l-4.788 4.788a2.625 2.625 0 0 1-3.712 0l-6.875-6.875A2.63 2.63 0 0 1 3 10.413V5.625A2.625 2.625 0 0 1 5.625 3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p6ou0pbzv) {
  d: path("M6.25 7.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

:global(.zdizkqbrb) {
  fill: currentColor;
  d: path("M10.75 14.75c0-2.5 1.5-4 4-4c0 2.5-1.5 4-4 4");
}

</style>
