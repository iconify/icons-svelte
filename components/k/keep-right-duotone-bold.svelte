<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gmtljk7jt"/><path class="myme2pb3l"/><path class="flz2zhftx"/><path class="bp3yu1oem"/><path class="d0n0p9bwt"/><path class="mz0o03tol"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:keep-right-duotone-bold" {...props}></Icon>
<style>
:global(.bp3yu1oem) {
  d: path("M12 22v-9l7 -7");
}

:global(.d0n0p9bwt) {
  d: path("M19 10.5V6h-4.5");
}

:global(.flz2zhftx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 11 5 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gmtljk7jt) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 22v-9l7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.myme2pb3l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 10.5V6h-4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mz0o03tol) {
  d: path("M10 11 5 6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
