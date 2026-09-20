<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="zqoml3bvy"/><path class="oe2rn1bbo"/><path class="gtsw5xviq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:leash-short-outline-bold" {...props}></Icon>
<style>
:global(.gtsw5xviq) {
  d: path("M17 5v14");
}

:global(.oe2rn1bbo) {
  d: path("M14 12h3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zqoml3bvy) {
  d: path("M11.11 7.47a5 5 0 1 1 -4.22 0");
}

</style>
