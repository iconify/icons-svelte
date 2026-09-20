<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ded97twic"/><path class="ogsy_iyfo"/><path class="rh0xrcajx"/><path class="uekn-bn9g"/><path class="l0iv52bbj"/><path class="kamdbib6v"/><path class="v-q4myyjv"/><path class="n2ya_p02p"/><path class="h5yksf4iw"/><path class="e3fkgnlsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:home-desk-duotone-bold" {...props}></Icon>
<style>
:global(.ded97twic) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 7h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.e3fkgnlsf) {
  d: path("M13 16h7");
}

:global(.h5yksf4iw) {
  d: path("M13 12h7");
}

:global(.kamdbib6v) {
  d: path("M2 7h20");
}

:global(.l0iv52bbj) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 16h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n2ya_p02p) {
  d: path("M13 7v13h7V7");
}

:global(.ogsy_iyfo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 7v13");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.rh0xrcajx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 7v13h7V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uekn-bn9g) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.v-q4myyjv) {
  d: path("M4 7v13");
}

</style>
