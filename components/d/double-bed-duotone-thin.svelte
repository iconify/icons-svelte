<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zdeiv7bia"/><path class="hvcr9mbrf"/><path class="ei8xo6bpl"/><path class="hpyzn1uwz"/><path class="et-iwmblh"/><path class="wg1ykyaxv"/><path class="rc8xkcb_g"/><path class="qitpg1b_y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:double-bed-duotone-thin" {...props}></Icon>
<style>
:global(.ei8xo6bpl) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 11V8h5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.et-iwmblh) {
  d: path("M2 18v-7h20v7");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hpyzn1uwz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 11V8h5v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hvcr9mbrf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 14.5h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qitpg1b_y) {
  d: path("M13 11V8h5v3");
}

:global(.rc8xkcb_g) {
  d: path("M4 11V8h5v3");
}

:global(.wg1ykyaxv) {
  d: path("M2 14.5h20");
}

:global(.zdeiv7bia) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18v-7h20v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
