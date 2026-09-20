<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ih7u9nbbo"/><path class="a2el1cxqo"/><path class="mwaecstwf"/><path class="p1z08ccdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:corner-left-up-duotone-regular" {...props}></Icon>
<style>
:global(.a2el1cxqo) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m5 9 5 -5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ih7u9nbbo) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 20H10V4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mwaecstwf) {
  d: path("M20 20H10V4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p1z08ccdv) {
  d: path("m5 9 5 -5 5 5");
}

</style>
