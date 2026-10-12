<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="v81x5hb6f"/><path class="b-skflb8e"/><rect class="bbhzcu2je"/><rect class="qay5a-vje"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:classifier" {...props}></Icon>
<style>
:global(.b-skflb8e) {
  d: path("m17.54 3.03l2.17 3.94q.29.53-.31.53h-4.3q-.6 0-.31-.53l2.17-3.94q.29-.53.58 0M6.75 10v2.25M17.25 10v2.25");
}

:global(.bbhzcu2je) {
  width: 8px;
  height: 7px;
  x: 2.75px;
  y: 14.25px;
  rx: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qay5a-vje) {
  width: 8px;
  height: 7px;
  x: 13.25px;
  y: 14.25px;
  rx: 2px;
}

:global(.v81x5hb6f) {
  cx: 6.75px;
  cy: 5.25px;
  r: 2.5px;
}

</style>
