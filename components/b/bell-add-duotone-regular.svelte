<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x6ei3vbab"/><path class="pga6n1bci"/><path class="sot87zl6h"/><path class="kdee3bb5f"/><path class="srzgk7jml"/><path class="jkuojibnm"/><path class="acx2mjbnt"/><path class="ikiprn9sq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bell-add-duotone-regular" {...props}></Icon>
<style>
:global(.acx2mjbnt) {
  d: path("M12 11v6");
}

:global(.ikiprn9sq) {
  d: path("M9 14h6");
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.kdee3bb5f) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 14h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pga6n1bci) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sot87zl6h) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 11v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.srzgk7jml) {
  d: path("M3 17a9 9 0 0 1 18 0");
}

:global(.x6ei3vbab) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
