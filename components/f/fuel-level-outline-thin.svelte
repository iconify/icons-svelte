<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l2nbo7bgf"/><path class="m-p3hbclp"/><path class="exre5jj_d"/><path class="jwnes9bsk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fuel-level-outline-thin" {...props}></Icon>
<style>
:global(.exre5jj_d) {
  d: path("m12 15 -4.5 -4.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
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

</style>
