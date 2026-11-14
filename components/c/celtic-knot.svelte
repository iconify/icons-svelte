<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j568z7b2h"/><path class="fmdezkbii"/><path class="fghzufttv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:celtic-knot" {...props}></Icon>
<style>
:global(.fghzufttv) {
  d: path("M3 19.75a9 9 0 0 1 18 0");
}

:global(.fmdezkbii) {
  d: path("M12 4.25a9 9 0 0 0 9 15.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j568z7b2h) {
  d: path("M12 4.25a9 9 0 0 1-9 15.5");
}

</style>
