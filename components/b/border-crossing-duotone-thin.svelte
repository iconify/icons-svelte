<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tsm_xmb_i"/><path class="z1kq20btb"/><path class="ibawpck_m"/><path class="o3rjf96zo"/><path class="zifm62gud"/><path class="q3srlnbfr"/><path class="mxzk029nb"/><path class="c438ceftc"/><path class="n96aj2bbi"/><path class="zpl29uvhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:border-crossing-duotone-thin" {...props}></Icon>
<style>
:global(.c438ceftc) {
  d: path("M12 17v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ibawpck_m) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 17v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mxzk029nb) {
  d: path("M12 10v4");
}

:global(.n96aj2bbi) {
  d: path("M4 12h15");
}

:global(.o3rjf96zo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 12h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.q3srlnbfr) {
  d: path("M12 2v5");
}

:global(.tsm_xmb_i) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 2v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z1kq20btb) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 10v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zifm62gud) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zpl29uvhf) {
  d: path("m16 9 3 3 -3 3");
}

</style>
