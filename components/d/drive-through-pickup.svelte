<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fwp0o5b3y"/><path class="qt0-pue7v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:drive-through-pickup" {...props}></Icon>
<style>
:global(.fwp0o5b3y) {
  d: path("M3 6.5L4.5 3h15L21 6.5m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0m-18 0v15m4.25-3H6V16l2.5-.5l2-3h6l2.5 3l2.5.5v2.5h-1.25m-8.5 0h4m-7.25-3H19m-5.5-3v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qt0-pue7v) {
  d: path("M7.75 18.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m8.5 0a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
