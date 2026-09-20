<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mekga68ar"/><path class="kw_wimh-t"/><path class="o1qccsp0v"/><path class="bp3yu1oem"/><path class="d0n0p9bwt"/><path class="mz0o03tol"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:keep-right-duotone-thin" {...props}></Icon>
<style>
:global(.bp3yu1oem) {
  d: path("M12 22v-9l7 -7");
}

:global(.d0n0p9bwt) {
  d: path("M19 10.5V6h-4.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kw_wimh-t) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M19 10.5V6h-4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mekga68ar) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 22v-9l7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mz0o03tol) {
  d: path("M10 11 5 6");
}

:global(.o1qccsp0v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 11 5 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
