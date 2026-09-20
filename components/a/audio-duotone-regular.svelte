<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z_7h9cc6w"/><path class="eiujlfb9c"/><path class="uw099db1h"/><path class="alzz4flpg"/><path class="ghzzdessy"/><path class="w74_pkbuu"/><path class="nj-oiubfo"/><path class="r7xk8o29f"/><path class="sunqexbsa"/><path class="om2raabrv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:audio-duotone-regular" {...props}></Icon>
<style>
:global(.alzz4flpg) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M16 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eiujlfb9c) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ghzzdessy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20 10v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nj-oiubfo) {
  d: path("M8 7v10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.om2raabrv) {
  d: path("M20 10v4");
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.sunqexbsa) {
  d: path("M16 7v10");
}

:global(.uw099db1h) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w74_pkbuu) {
  d: path("M4 10v4");
}

:global(.z_7h9cc6w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 10v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
