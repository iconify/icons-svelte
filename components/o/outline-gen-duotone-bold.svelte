<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h7vr07ufd"/><path class="bxipa2bar"/><path class="s0-7f3bev"/><path class="mg_6zl_av"/><path class="k6nj2fbya"/><path class="r1-ktgx-e"/><path class="nmmozg1gr"/><path class="t33f_gbzo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:outline-gen-duotone-bold" {...props}></Icon>
<style>
:global(.bxipa2bar) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 10h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h7vr07ufd) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 5h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.k6nj2fbya) {
  d: path("M3 5h18");
}

:global(.mg_6zl_av) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 20h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nmmozg1gr) {
  d: path("M7 15h14");
}

:global(.r1-ktgx-e) {
  d: path("M7 10h14");
}

:global(.s0-7f3bev) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 15h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t33f_gbzo) {
  d: path("M11 20h10");
}

</style>
