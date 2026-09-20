<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="n8sts3-0i"/><path class="kb7unlbzd"/><path class="fjp0md11r"/><path class="zl6g0h25d"/><path class="r3faxubne"/><path class="ler50rfbf"/><path class="siun7_bal"/><path class="cub64ac5a"/><path class="cjsg0ab2y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:retention-duotone-thin" {...props}></Icon>
<style>
:global(.cjsg0ab2y) {
  d: path("M2 20h20");
}

:global(.cub64ac5a) {
  d: path("M19 13v7");
}

:global(.fjp0md11r) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 13v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gms_xv68n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kb7unlbzd) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 11v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ler50rfbf) {
  d: path("M9 8v12");
}

:global(.n8sts3-0i) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.siun7_bal) {
  d: path("M14 11v9");
}

:global(.zl6g0h25d) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 20h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
