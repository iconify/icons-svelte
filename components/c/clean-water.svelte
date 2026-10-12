<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ldzsy3bwp"/><path class="vgewaswlr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:clean-water" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ldzsy3bwp) {
  d: path("M10.5 4.25c3.5 3.9 5.75 7.2 5.75 10.25a5.75 5.75 0 0 1-11.5 0c0-3.05 2.25-6.35 5.75-10.25");
}

:global(.vgewaswlr) {
  d: path("M7.75 15A2.75 2.75 0 0 0 10 17.5m8.25-14.75q.36 2.64 3 3q-2.64.36-3 3q-.36-2.64-3-3q2.64-.36 3-3");
}

</style>
