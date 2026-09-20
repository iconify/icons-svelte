<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dx5s6zbrc"/><path class="yseexlbcu"/><path class="syrab3bug"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:candy-outline-regular" {...props}></Icon>
<style>
:global(.dx5s6zbrc) {
  d: path("M8 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.syrab3bug) {
  d: path("M15.5 9.5 19 6v12l-3.5 -3.5");
}

:global(.yseexlbcu) {
  d: path("M8.5 9.5 5 6v12l3.5 -3.5");
}

</style>
