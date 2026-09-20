<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tt-5y-ilt"/><path class="rfwgx-bjs"/><path class="c0jxsvbmy"/><path class="b0695_86h"/><path class="l2nbo7bgf"/><path class="m-p3hbclp"/><path class="exre5jj_d"/><path class="jwnes9bsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fuel-level-duotone-bold" {...props}></Icon>
<style>
:global(.b0695_86h) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 19h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c0jxsvbmy) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m12 15 -4.5 -4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.exre5jj_d) {
  d: path("m12 15 -4.5 -4.5");
}

:global(.jwnes9bsk) {
  d: path("M8 19h8");
}

:global(.l2nbo7bgf) {
  d: path("M4 15a8 8 0 0 1 16 0");
}

:global(.m-p3hbclp) {
  d: path("M4 15h16");
}

:global(.rfwgx-bjs) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 15h16");
  opacity: var(--svg-opacity--0-2, 0.2);
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

</style>
