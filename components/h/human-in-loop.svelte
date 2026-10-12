<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s86wwrbuj"/><circle class="kz9qc0sgp"/><path class="ildoaibfm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:human-in-loop" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ildoaibfm) {
  d: path("M7.5 20.25c0-3 2-5.25 4.5-5.25s4.5 2.25 4.5 5.25a1 1 0 0 1-1 1h-7a1 1 0 0 1-1-1");
}

:global(.kz9qc0sgp) {
  cx: 12px;
  cy: 9.75px;
  r: 2.25px;
}

:global(.s86wwrbuj) {
  d: path("M6.15 13.13a6.75 6.75 0 1 1 11.7 0m2.41-.65l-2.41.65l-.65-2.42");
}

</style>
