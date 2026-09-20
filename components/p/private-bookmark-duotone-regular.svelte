<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xdwo9hb6a"/><path class="i4kdkubna"/><path class="wv6md6qod"/><path class="ywmylfbpm"/><path class="v60hotbkj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:private-bookmark-duotone-regular" {...props}></Icon>
<style>
:global(.i4kdkubna) {
  fill: currentColor;
  d: path("M9 8.5h6v3H9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v60hotbkj) {
  d: path("M10.5 8.5a1.5 1.5 0 0 1 3 0");
}

:global(.wv6md6qod) {
  d: path("M15 3h3v18l-6 -6 -6 6V3h3");
}

:global(.xdwo9hb6a) {
  fill: currentColor;
  d: path("M15 3h3v18l-6 -6 -6 6V3h3");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ywmylfbpm) {
  d: path("M9 8.5h6v3H9Z");
}

</style>
