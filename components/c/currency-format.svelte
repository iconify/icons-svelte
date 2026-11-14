<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tux3sqb_r"/><path class="z1ksjibwx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:currency-format" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.tux3sqb_r) {
  d: path("M6.5 5.5h11A3.5 3.5 0 0 1 21 9v6a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 15V9a3.5 3.5 0 0 1 3.5-3.5");
}

:global(.z1ksjibwx) {
  d: path("M14 9.75c-.75-1.25-4-1.25-4 .75s4 1 4 3s-3.25 2-4 .75m2-6.5v8.5");
}

</style>
