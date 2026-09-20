<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="knhft4qdm"/><path class="s30vxrb5b"/><path class="pga6n1bci"/><path class="evlaqhbnc"/><path class="rjl8fe1sw"/><path class="qq9-4ficr"/><path class="jkuojibnm"/><path class="o1o-p0bmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:admission-webhook-duotone-regular" {...props}></Icon>
<style>
:global(.evlaqhbnc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m19 7 -4 4h3l-4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.knhft4qdm) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 6v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o1o-p0bmq) {
  d: path("m19 7 -4 4h3l-4 4");
}

:global(.pga6n1bci) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qq9-4ficr) {
  d: path("m4 13 9 -9");
}

:global(.rjl8fe1sw) {
  d: path("M4 6v14");
}

:global(.s30vxrb5b) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 13 9 -9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
