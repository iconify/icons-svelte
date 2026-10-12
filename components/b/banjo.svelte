<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="opyybkahz"/><path class="sz_walmzk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:banjo" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.opyybkahz) {
  cx: 8.5px;
  cy: 15.5px;
  r: 5.75px;
}

:global(.sz_walmzk) {
  d: path("m6.6 16.15l1.75 1.75m4.22-6.47l5.28-5.28m1.93-2.64l.71.71q.53.53 0 1.06l-1.41 1.41q-.53.53-1.06 0l-.71-.71q-.53-.53 0-1.06l1.41-1.41q.53-.53 1.06 0");
}

</style>
