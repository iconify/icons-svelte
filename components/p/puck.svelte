<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u6ik4k8wl"/><path class="a_0g7mbyb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:puck" {...props}></Icon>
<style>
:global(.a_0g7mbyb) {
  d: path("M2.75 10c0 2.35 4.14 4.25 9.25 4.25s9.25-1.9 9.25-4.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.u6ik4k8wl) {
  d: path("M2.75 10c0-2.35 4.14-4.25 9.25-4.25s9.25 1.9 9.25 4.25v4c0 2.35-4.14 4.25-9.25 4.25S2.75 16.35 2.75 14Z");
}

</style>
