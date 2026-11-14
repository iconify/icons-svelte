<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jmy8g-bee"/><path class="p6ovsxlir"/><path class="z80-_0b0x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:photo-print-service" {...props}></Icon>
<style>
:global(.jmy8g-bee) {
  d: path("M2.5 7h19v8h-19Zm4 0V2.5h11V7");
}

:global(.p6ovsxlir) {
  d: path("M6.5 12v9.5h11V12M5 12h14");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.z80-_0b0x) {
  d: path("m8 20l3-3.5l2 2l1.25-1.25l1.75 2");
}

</style>
