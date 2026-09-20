<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ngf5sgn5h"/><path class="uq6n7rbdt"/><path class="axa755czi"/><path class="fco1n9k6o"/><path class="r4nj1cczx"/><path class="sxy07wbdf"/><path class="eu9kkgbdm"/><path class="x3jqftbaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:groupby-duotone-regular" {...props}></Icon>
<style>
:global(.axa755czi) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 12h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.eu9kkgbdm) {
  d: path("M9 12h12");
}

:global(.fco1n9k6o) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 17h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ngf5sgn5h) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 4H3v16h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r4nj1cczx) {
  d: path("M6 4H3v16h3");
}

:global(.sxy07wbdf) {
  d: path("M9 7h12");
}

:global(.uq6n7rbdt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 7h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x3jqftbaj) {
  d: path("M9 17h12");
}

</style>
