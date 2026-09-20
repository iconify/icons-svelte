<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fhtkkzo7b"/><path class="tt-5y-ilt"/><path class="ycftzzhuq"/><path class="l2nbo7bgf"/><path class="l8dn9jbyp"/><path class="ghgpbwtop"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:catering-duotone-bold" {...props}></Icon>
<style>
:global(.fhtkkzo7b) {
  fill: currentColor;
  d: path("M11 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ghgpbwtop) {
  d: path("M11 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.l2nbo7bgf) {
  d: path("M4 15a8 8 0 0 1 16 0");
}

:global(.l8dn9jbyp) {
  d: path("M2 15h20");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tt-5y-ilt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 15a8 8 0 0 1 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ycftzzhuq) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 15h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
