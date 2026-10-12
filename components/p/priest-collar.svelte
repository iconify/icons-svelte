<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lqruq4dyu"/><rect class="f68z5pbkt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:priest-collar" {...props}></Icon>
<style>
:global(.f68z5pbkt) {
  width: 2.5px;
  height: 2.75px;
  x: 10.75px;
  y: 14.75px;
  rx: 0.5px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lqruq4dyu) {
  d: path("M2.75 21.25V17c0-1.5 1-2.5 2.5-3L9 12.5q1.125 2.25 3 2.25c1.875 0 2.25-.75 3-2.25l3.75 1.5c1.5.5 2.5 1.5 2.5 3v4.25Z");
}

</style>
