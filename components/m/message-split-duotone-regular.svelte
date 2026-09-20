<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="znztjab3f"/><path class="hniq9v4ac"/><path class="x6m99nb0u"/><path class="j2xpj8b3j"/><path class="msusn6nui"/><path class="n-059ea3n"/><path class="vxqaiwbbu"/><path class="gcu5j9bzw"/><path class="wo23ajbmh"/><path class="rm0jxkbqz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:message-split-duotone-regular" {...props}></Icon>
<style>
:global(.gcu5j9bzw) {
  d: path("M14 4h3v3");
}

:global(.hniq9v4ac) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 12 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j2xpj8b3j) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9 12 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.msusn6nui) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 20h3v-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.n-059ea3n) {
  d: path("M5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rm0jxkbqz) {
  d: path("M14 20h3v-3");
}

:global(.vxqaiwbbu) {
  d: path("m9 12 8 -8");
}

:global(.wo23ajbmh) {
  d: path("m9 12 8 8");
}

:global(.x6m99nb0u) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 4h3v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.znztjab3f) {
  fill: currentColor;
  d: path("M5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
