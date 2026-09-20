<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="atcqm9b8v"/><path class="z81oy96ne"/><path class="uawgdrhah"/><path class="dlffxm03j"/><path class="ucd8o6bjf"/><path class="nbncjhbtk"/><path class="qp5e0_b3n"/><path class="tdk6nzbaw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:event-stream-duotone-regular" {...props}></Icon>
<style>
:global(.atcqm9b8v) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2.5 2.5 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.dlffxm03j) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M20.5 17v3.5H17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nbncjhbtk) {
  d: path("M7.5 7.5 10 10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qp5e0_b3n) {
  d: path("M12.5 12.5 15 15");
}

:global(.tdk6nzbaw) {
  d: path("M20.5 17v3.5H17");
}

:global(.uawgdrhah) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12.5 12.5 15 15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ucd8o6bjf) {
  d: path("M2.5 2.5 5 5");
}

:global(.z81oy96ne) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.5 7.5 10 10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
