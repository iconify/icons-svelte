<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dh-nlhghu"/><path class="jiw8u-asa"/><path class="rh7yi0b-t"/><path class="qshjs6bnh"/><path class="c948_kypl"/><path class="aeubruljt"/><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="p4gh801hs"/><path class="qui36tb8q"/><path class="ygselab1a"/><path class="plvacbczu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rollup-metric-duotone-bold" {...props}></Icon>
<style>
:global(.aeubruljt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 7v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c948_kypl) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dh-nlhghu) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jiw8u-asa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.p4gh801hs) {
  d: path("M8 14v4");
}

:global(.plvacbczu) {
  d: path("M18 7v11");
}

:global(.qshjs6bnh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 12v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qui36tb8q) {
  d: path("M11 12v6");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.rh7yi0b-t) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 14v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ygselab1a) {
  d: path("M14 15v3");
}

</style>
