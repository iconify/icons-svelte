<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x_gl3dqww"/><path class="lp6809jwr"/><path class="io5188b_g"/><path class="ps3-67b_v"/><path class="wlia6bb5b"/><path class="adiugjbhs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:encoder-duotone-bold" {...props}></Icon>
<style>
:global(.adiugjbhs) {
  d: path("m15 9 3 3 -3 3");
}

:global(.io5188b_g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m15 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.lp6809jwr) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ps3-67b_v) {
  d: path("m4 3 6 6v6l-6 6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wlia6bb5b) {
  d: path("M11 12h7");
}

:global(.x_gl3dqww) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 3 6 6v6l-6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
