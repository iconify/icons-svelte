<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="be306ynmy"/><path class="imbfzub2u"/><path class="ewy1wiqaa"/><path class="osd88_fjp"/><path class="ex75cacie"/><path class="xgrfb-bqu"/><path class="o759xmblc"/><path class="h7bcztycq"/><path class="c27cgq4un"/><path class="xyj-l9cjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:normalize-duotone-regular" {...props}></Icon>
<style>
:global(.be306ynmy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c27cgq4un) {
  d: path("M18 8v8");
}

:global(.ewy1wiqaa) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ex75cacie) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h7bcztycq) {
  d: path("M12 8v8");
}

:global(.imbfzub2u) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o759xmblc) {
  d: path("M6 8v8");
}

:global(.osd88_fjp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xgrfb-bqu) {
  d: path("M3 6h18");
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

</style>
