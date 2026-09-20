<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hbdbg_bcy"/><path class="lyjarcbwz"/><path class="ok51kk6mj"/><path class="yqfc2tb5a"/><path class="ae31urzdd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chat-diff-outline-thin" {...props}></Icon>
<style>
:global(.ae31urzdd) {
  d: path("M13 10h4");
}

:global(.hbdbg_bcy) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lyjarcbwz) {
  d: path("M7 18v3l3 -3");
}

:global(.ok51kk6mj) {
  d: path("M9 8v4");
}

:global(.yqfc2tb5a) {
  d: path("M7 10h4");
}

</style>
