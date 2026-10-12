<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lk8bykbzk"/><circle class="p_flhjbml"/><path class="t7yjaxier"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:alt-text" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lk8bykbzk) {
  d: path("M11.25 20.25h-6a2.5 2.5 0 0 1-2.5-2.5V6.25a2.5 2.5 0 0 1 2.5-2.5h13.5a2.5 2.5 0 0 1 2.5 2.5v4.5");
}

:global(.p_flhjbml) {
  cx: 8.5px;
  cy: 9px;
  r: 1.75px;
}

:global(.t7yjaxier) {
  d: path("m2.75 16.25l4.1-4.1a1.6 1.6 0 0 1 2.25 0l2.4 2.4m1.75.7a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v2.5a2 2 0 0 1-2 2h-3.5l-2.5 1.5Zm2.5 1.25h3");
}

</style>
