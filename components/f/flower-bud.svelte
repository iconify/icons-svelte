<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ilji6mbvl"/><circle class="z-ze1jbyb"/><path class="qoktzjbvh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:flower-bud" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ilji6mbvl) {
  d: path("M13.91 6.37A2.25 2.25 0 1 1 15.09 10A2.25 2.25 0 1 1 12 12.25A2.25 2.25 0 1 1 8.91 10a2.25 2.25 0 1 1 1.18-3.63a2.25 2.25 0 1 1 3.82 0");
}

:global(.qoktzjbvh) {
  d: path("M12 13.75v7.5m0-1.5C12.5 18 14.25 17 16.5 17c-.5 1.75-2.25 2.75-4.5 2.75");
}

:global(.z-ze1jbyb) {
  cx: 12px;
  cy: 9px;
  r: 1.5px;
}

</style>
