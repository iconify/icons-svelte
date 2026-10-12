<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wrmy9klhs"/><rect class="mw7l5rs4l"/><path class="ezrzdhswm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cattail" {...props}></Icon>
<style>
:global(.ezrzdhswm) {
  d: path("M9.25 12v9.25m0-16.75V2.75M16 14v7.25M16 7.5V5.75m-3.5 15.5c.25-3.5-.25-6.5-1.25-8.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mw7l5rs4l) {
  width: 3.5px;
  height: 6.5px;
  x: 14.25px;
  y: 7.5px;
  rx: 1.75px;
}

:global(.wrmy9klhs) {
  width: 3.5px;
  height: 7.5px;
  x: 7.5px;
  y: 4.5px;
  rx: 1.75px;
}

</style>
