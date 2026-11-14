<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jsatwlp0c"/><path class="rbv9ltwdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:altar-table" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jsatwlp0c) {
  d: path("M3 21.5V12h18v9.5");
}

:global(.rbv9ltwdm) {
  d: path("m3 16.5l9 2.5l9-2.5m-9.5-11h1A1.5 1.5 0 0 1 14 7v3.5a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5V7a1.5 1.5 0 0 1 1.5-1.5M12 3h.01");
}

</style>
