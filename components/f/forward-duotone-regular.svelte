<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pfs703iee"/><path class="xls6es23o"/><path class="s1ev1ubdz"/><path class="f8wj1yoym"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:forward-duotone-regular" {...props}></Icon>
<style>
:global(.f8wj1yoym) {
  d: path("M21 9H7v11");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pfs703iee) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 4 5 5 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.s1ev1ubdz) {
  d: path("m16 4 5 5 -5 5");
}

:global(.xls6es23o) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 9H7v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
