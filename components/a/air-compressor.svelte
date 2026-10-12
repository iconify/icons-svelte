<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="cjsgmow4x"/><circle class="sb4kn6-oq"/><path class="gjy7smbsp"/><path class="l63cci3ci"/><path class="bshrrcgek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:air-compressor" {...props}></Icon>
<style>
:global(.bshrrcgek) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 15.75v5");
}

:global(.cjsgmow4x) {
  width: 18.5px;
  height: 6.25px;
  x: 2.75px;
  y: 9.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 3.125px;
}

:global(.gjy7smbsp) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.75V9.5");
}

:global(.l63cci3ci) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.5 19.5h.01");
}

:global(.sb4kn6-oq) {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
