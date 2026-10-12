<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a53x0gzdu"/><circle class="oiqjdxbpf"/><path class="zx7f2ubhr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dental-mirror" {...props}></Icon>
<style>
:global(.a53x0gzdu) {
  d: path("M3.5 20.5L10 14l2.85-4.95");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.oiqjdxbpf) {
  cx: 14.5px;
  cy: 6.25px;
  r: 3.25px;
}

:global(.zx7f2ubhr) {
  d: path("M14.5 14.5a2 2 0 0 1 3-1.75a2 2 0 0 1 3 1.75c0 2-.5 3-.75 4.5l-.5 2.25h-1l-.75-3l-.75 3h-1l-.5-2.25c-.25-1.5-.75-2.5-.75-4.5");
}

</style>
