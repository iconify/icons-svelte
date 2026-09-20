<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ef2afnbgy"/><path class="oqfv9rb9x"/><path class="yvwbi-etd"/><path class="lmoarbbkf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:embassy-outline-thin" {...props}></Icon>
<style>
:global(.ef2afnbgy) {
  d: path("M4 21V10h16v11");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.lmoarbbkf) {
  d: path("M12 3h7v4h-7");
}

:global(.oqfv9rb9x) {
  d: path("M2 21h20");
}

:global(.yvwbi-etd) {
  d: path("M12 2v8");
}

</style>
