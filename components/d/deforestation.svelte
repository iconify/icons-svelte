<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zff3-zpji"/><path class="bm7getb6a"/><path class="cv8uu5uva"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:deforestation" {...props}></Icon>
<style>
:global(.bm7getb6a) {
  d: path("M5 12.5V19l-1 2h16l-1-2v-6.5");
}

:global(.cv8uu5uva) {
  d: path("M9.5 12.5a2.5 1.25 0 1 0 5 0a2.5 1.25 0 1 0-5 0M14 9.25V5.5h3V10m-1.5-4.5l4.5-3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zff3-zpji) {
  d: path("M5 12.5a7 3.5 0 1 0 14 0a7 3.5 0 1 0-14 0");
}

</style>
