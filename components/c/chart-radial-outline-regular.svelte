<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m5e7pz7_z"/><path class="n6apnpbtf"/><path class="cs--63jny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chart-radial-outline-regular" {...props}></Icon>
<style>
:global(.cs--63jny) {
  d: path("M12 2a10 10 0 1 1 -7.07 2.93");
}

:global(.m5e7pz7_z) {
  d: path("M12 8a4 4 0 0 1 0 8");
}

:global(.n6apnpbtf) {
  d: path("M12 5a7 7 0 1 1 -7 7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
