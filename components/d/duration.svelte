<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dh-xp411l"/><path class="xe6w-fs3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:duration" {...props}></Icon>
<style>
:global(.dh-xp411l) {
  cx: 12px;
  cy: 9.5px;
  r: 6.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xe6w-fs3d) {
  d: path("M12 6.25V9.5l2 1.25m-10.25 7.5v3m16.5-3v3m-16.5-1.5h16.5");
}

</style>
