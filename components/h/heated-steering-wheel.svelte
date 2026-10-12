<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="ydy0opbpr"/><circle class="c-m5iogoj"/><path class="gc_xfhkcy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:heated-steering-wheel" {...props}></Icon>
<style>
:global(.c-m5iogoj) {
  cx: 12px;
  cy: 15.5px;
  r: 1.75px;
}

:global(.gc_xfhkcy) {
  d: path("M6.25 15.5h4m3.5 0h4M12 17.25v4M8.5 6.75c-.75-.75.75-1.25 0-2s.75-1.25 0-2m3.5 4c-.75-.75.75-1.25 0-2s.75-1.25 0-2m3.5 4c-.75-.75.75-1.25 0-2s.75-1.25 0-2");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ydy0opbpr) {
  cx: 12px;
  cy: 15.5px;
  r: 5.75px;
}

</style>
