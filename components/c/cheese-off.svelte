<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vr9fj3obz"/><path class="xiteq3bjl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cheese-off" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vr9fj3obz) {
  d: path("m3.25 11.25l10-6.5l7.5 4v10.5a2 2 0 0 1-2 2H5.25a2 2 0 0 1-2-2Zm0 0h17.5");
}

:global(.xiteq3bjl) {
  d: path("M6.75 15.75a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M13 17a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
