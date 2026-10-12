<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qw5hxjj5i"/><rect class="j0k70rb3p"/><rect class="zfo5aacpv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:allowance-jar" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j0k70rb3p) {
  width: 8.5px;
  height: 2.5px;
  x: 7.75px;
  y: 6px;
  rx: 1.25px;
}

:global(.qw5hxjj5i) {
  d: path("M9.5 6a2.5 2.5 0 0 1 5 0Z");
}

:global(.zfo5aacpv) {
  width: 13.5px;
  height: 9.75px;
  x: 5.25px;
  y: 11.5px;
  rx: 3.5px;
}

</style>
