<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="yu-j7jb_g"/><path class="ca-a_rbiv"/><path class="dhf53kbbi"/><path class="h7s_qlkps"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="u8oheccad"/><path class="mq159kbup"/><path class="m-y6zjb5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:refusal-rate-duotone-thin" {...props}></Icon>
<style>
:global(.ca-a_rbiv) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dhf53kbbi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gms_xv68n) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h7s_qlkps) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m-y6zjb5q) {
  d: path("M16 15v3");
}

:global(.mq159kbup) {
  d: path("M12 15v3");
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.u8oheccad) {
  d: path("M8 15v3");
}

:global(.yu-j7jb_g) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
