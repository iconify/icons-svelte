<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iw6xucujz"/><path class="i_rxvmb8k"/><path class="dx3ubrb9h"/><path class="hbtmd5b0k"/><path class="f-d09l9vj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:dependency-audit-duotone-thin" {...props}></Icon>
<style>
:global(.dx3ubrb9h) {
  d: path("M4 7.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2V19a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

:global(.f-d09l9vj) {
  d: path("M9 10.5h6v3l-3 3 -3 -3Z");
}

:global(.hbtmd5b0k) {
  d: path("M9.5 7V2.5h5V7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i_rxvmb8k) {
  fill: currentColor;
  d: path("M9 10.5h6v3l-3 3 -3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.iw6xucujz) {
  fill: currentColor;
  d: path("M4 7.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2V19a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
