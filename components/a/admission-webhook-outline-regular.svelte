<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rjl8fe1sw"/><path class="qq9-4ficr"/><path class="jkuojibnm"/><path class="o1o-p0bmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:admission-webhook-outline-regular" {...props}></Icon>
<style>
:global(.jkuojibnm) {
  d: path("M3 20h18");
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

:global(.qq9-4ficr) {
  d: path("m4 13 9 -9");
}

:global(.rjl8fe1sw) {
  d: path("M4 6v14");
}

</style>
