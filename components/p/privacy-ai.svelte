<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b5iy4umwa"/><rect class="r6-o0bcpk"/><path class="mrfl2obow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:privacy-ai" {...props}></Icon>
<style>
:global(.b5iy4umwa) {
  d: path("M8 10.25V7.5a4 4 0 0 1 8 0v2.75");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mrfl2obow) {
  d: path("M12 12.25q.42 3.08 3.5 3.5q-3.08.42-3.5 3.5q-.42-3.08-3.5-3.5q3.08-.42 3.5-3.5");
}

:global(.r6-o0bcpk) {
  width: 14.5px;
  height: 11px;
  x: 4.75px;
  y: 10.25px;
  rx: 2.5px;
}

</style>
