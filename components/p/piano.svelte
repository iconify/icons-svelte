<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r41-hxbqt"/><rect class="jcbg22mos"/><path class="o2gbzzbrr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:piano" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jcbg22mos) {
  width: 16.5px;
  height: 3.75px;
  x: 3.75px;
  y: 17.5px;
  rx: 1px;
}

:global(.o2gbzzbrr) {
  d: path("M7.75 17.5v3.75M12 17.5v3.75m4.25-3.75v3.75");
}

:global(.r41-hxbqt) {
  d: path("M4.75 17.5v-12C4.75 4 6 2.75 7.5 2.75S10.25 4 10.25 5.5c0 3.5 2.25 5 5.25 6.75c2.5 1.45 3.75 3.25 3.75 5.25Z");
}

</style>
