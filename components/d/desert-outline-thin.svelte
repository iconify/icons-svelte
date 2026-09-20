<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pemn838wn"/><path class="a78gppbhl"/><path class="ixxrscbjj"/><path class="fxla4ib-b"/><path class="tpi3f12bz"/><path class="z9ittvbis"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:desert-outline-thin" {...props}></Icon>
<style>
:global(.a78gppbhl) {
  d: path("M6 6h2.5");
}

:global(.fxla4ib-b) {
  d: path("M2 19a6 6 0 0 1 12 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ixxrscbjj) {
  d: path("M15.5 6H18");
}

:global(.pemn838wn) {
  d: path("M9 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.tpi3f12bz) {
  d: path("M12 19a5 5 0 0 1 10 0");
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
