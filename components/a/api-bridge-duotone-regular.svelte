<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h78mtnbkg"/><path class="amdyfrbnw"/><path class="u-kmlrghs"/><path class="fzmgr7bvw"/><path class="md3qg6xkk"/><path class="bvirm9d4j"/><path class="sxlwlmkmh"/><path class="n90p24bmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:api-bridge-duotone-regular" {...props}></Icon>
<style>
:global(.amdyfrbnw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.bvirm9d4j) {
  d: path("M20 6v12");
}

:global(.fzmgr7bvw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 10 2 2 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h78mtnbkg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 6v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.md3qg6xkk) {
  d: path("M4 6v12");
}

:global(.n90p24bmq) {
  d: path("m10 10 2 2 -2 2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.sxlwlmkmh) {
  d: path("M4 12h16");
}

:global(.u-kmlrghs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 12h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
