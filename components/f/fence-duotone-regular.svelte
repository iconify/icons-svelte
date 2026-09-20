<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xoqp_ei8h"/><path class="xe12qkbct"/><path class="bw_hjebim"/><path class="xp9zz1bcs"/><path class="p1vo9wptt"/><path class="s_uvnuivb"/><path class="uhty14kih"/><path class="f50v0cimy"/><path class="v5d935don"/><path class="ef5tcc6_c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fence-duotone-regular" {...props}></Icon>
<style>
:global(.bw_hjebim) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ef5tcc6_c) {
  d: path("M4 16h14");
}

:global(.f50v0cimy) {
  d: path("M18 7v14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p1vo9wptt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 16h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s_uvnuivb) {
  d: path("M4 7v14");
}

:global(.uhty14kih) {
  d: path("M11 7v14");
}

:global(.v5d935don) {
  d: path("M4 11h14");
}

:global(.xe12qkbct) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xoqp_ei8h) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 7v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xp9zz1bcs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 11h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
