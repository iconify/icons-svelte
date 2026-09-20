<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w08657bnd"/><path class="icy6dnbvy"/><path class="n-7t0yb1r"/><path class="esz0ytbwn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:balance-training-outline-regular" {...props}></Icon>
<style>
:global(.esz0ytbwn) {
  d: path("M8 17a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.icy6dnbvy) {
  d: path("M12 8v5");
}

:global(.n-7t0yb1r) {
  d: path("M3 13h18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.w08657bnd) {
  d: path("M9 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
