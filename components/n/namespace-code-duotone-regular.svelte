<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ibuanu9pl"/><path class="ps2g__eqt"/><path class="qbzh-xbpw"/><path class="y49yakb9n"/><path class="uk7acdcay"/><path class="lzdsnnb7v"/><path class="epou1mbuy"/><path class="b4de0eyhw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:namespace-code-duotone-regular" {...props}></Icon>
<style>
:global(.b4de0eyhw) {
  d: path("M16 4h4v16h-4");
}

:global(.epou1mbuy) {
  d: path("M11 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.ibuanu9pl) {
  fill: currentColor;
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lzdsnnb7v) {
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ps2g__eqt) {
  fill: currentColor;
  d: path("M11 16a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qbzh-xbpw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 4H4v16h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uk7acdcay) {
  d: path("M8 4H4v16h4");
}

:global(.y49yakb9n) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 4h4v16h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
