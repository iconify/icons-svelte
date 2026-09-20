<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kbnq5bc4a"/><path class="dk5jyixqt"/><path class="i2-ny_bzf"/><path class="mxzk029nb"/><path class="ffs26fbkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flip-horizontal-outline-regular" {...props}></Icon>
<style>
:global(.dk5jyixqt) {
  d: path("m15 5 7 7 -7 7Z");
}

:global(.ffs26fbkv) {
  d: path("M12 17v4");
}

:global(.i2-ny_bzf) {
  d: path("M12 3v4");
}

:global(.kbnq5bc4a) {
  d: path("m9 5 -7 7 7 7Z");
}

:global(.mxzk029nb) {
  d: path("M12 10v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
