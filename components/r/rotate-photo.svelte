<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="salrgsbgu"/><path class="nx02e6ksh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:rotate-photo" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nx02e6ksh) {
  d: path("m2.75 18.25l3.5-3.5L10.5 19m-1-1l1.5-1.5l3.75 3.75m-2-16.5A6.25 6.25 0 0 1 19 10v2.25M16.75 10L19 12.25L21.25 10");
}

:global(.salrgsbgu) {
  width: 12px;
  height: 12px;
  x: 2.75px;
  y: 9.25px;
  rx: 2px;
}

</style>
