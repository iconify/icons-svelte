<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ld656tbbe"/><path class="rd192gboy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:card-heart" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ld656tbbe) {
  width: 14.5px;
  height: 18.5px;
  x: 4.75px;
  y: 2.75px;
  rx: 2.25px;
}

:global(.rd192gboy) {
  d: path("M12 17c-2.75-1.75-5-3.75-5-6.25a2.5 2.5 0 0 1 5-.75a2.5 2.5 0 0 1 5 .75c0 2.5-2.25 4.5-5 6.25");
}

</style>
