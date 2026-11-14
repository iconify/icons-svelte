<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n-72-2i3a"/><path class="rtyreacza"/><path class="xrfa8fz1m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:factory-clock" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n-72-2i3a) {
  d: path("M3 19.5V8l6-3.5V8l6-3.5V8l6-3.5v15Z");
}

:global(.rtyreacza) {
  d: path("M8 13.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

:global(.xrfa8fz1m) {
  d: path("M12 11v2.5h2");
}

</style>
