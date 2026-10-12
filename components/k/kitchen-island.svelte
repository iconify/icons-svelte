<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="e5jxrjfda"/><path class="zoq935b3v"/><path class="jqha4tb8j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:kitchen-island" {...props}></Icon>
<style>
:global(.e5jxrjfda) {
  width: 18.5px;
  height: 3.5px;
  x: 2.75px;
  y: 6.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

:global(.jqha4tb8j) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 14.75h.01m3.99 0h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zoq935b3v) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 12.25h14.5v7a2 2 0 0 1-2 2H6.75a2 2 0 0 1-2-2Zm7.25 0v9");
}

</style>
