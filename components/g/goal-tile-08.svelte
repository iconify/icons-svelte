<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i53jb3bnv"/><path class="r28p-jmoo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:goal-tile-08" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i53jb3bnv) {
  d: path("M2.5 19.5V5h19v14.5");
}

:global(.r28p-jmoo) {
  d: path("m2.5 5l4 3.5v11m0-11h11v11m0-11l4-3.5M12 8.5v11");
}

</style>
