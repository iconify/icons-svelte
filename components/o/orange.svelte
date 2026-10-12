<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="w6czd5b3h"/><path class="hpwbfkdsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:orange" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hpwbfkdsk) {
  d: path("M12.5 5.25c0-1.25.75-2.25 2.5-2.5C15 4 14.25 5 12.5 5.25M7 13a5 5 0 0 1 2.5-4.35");
}

:global(.w6czd5b3h) {
  cx: 12px;
  cy: 13.25px;
  r: 8px;
}

</style>
