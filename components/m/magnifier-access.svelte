<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="y-fd6pbmc"/><path class="vb9vl1bic"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:magnifier-access" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vb9vl1bic) {
  d: path("m15.75 15.75l5.5 5.5M7.5 13.5L10.25 7L13 13.5m-4.5-2.25H12");
}

:global(.y-fd6pbmc) {
  cx: 10.25px;
  cy: 10.25px;
  r: 7.5px;
}

</style>
