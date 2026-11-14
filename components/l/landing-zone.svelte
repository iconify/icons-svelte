<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lizzrcblo"/><path class="xtg22db0a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:landing-zone" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lizzrcblo) {
  d: path("M3 10.5a9 5 0 1 0 18 0a9 5 0 1 0-18 0M2.5 19h19");
}

:global(.xtg22db0a) {
  d: path("M7.5 10.5a4.5 2 0 1 0 9 0a4.5 2 0 1 0-9 0");
}

</style>
