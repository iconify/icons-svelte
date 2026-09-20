<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dayy5pxdu"/><path class="oq8gkl3jk"/><path class="kw9oa7xce"/><path class="cdily2n9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevrons-down-duotone-regular" {...props}></Icon>
<style>
:global(.cdily2n9h) {
  d: path("m4 13 8 8 8 -8");
}

:global(.dayy5pxdu) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 4 8 8 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.kw9oa7xce) {
  d: path("m4 4 8 8 8 -8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oq8gkl3jk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 13 8 8 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
