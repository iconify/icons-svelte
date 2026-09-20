<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uk0rveqaj"/><path class="rdx5t34om"/><path class="aq5i5tblx"/><path class="p83l94bht"/><path class="zvg3vyivl"/><path class="e8mk-vdvn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:knowledge-graph-outline-thin" {...props}></Icon>
<style>
:global(.aq5i5tblx) {
  d: path("M4 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.e8mk-vdvn) {
  d: path("M6 9v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p83l94bht) {
  d: path("M16 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.rdx5t34om) {
  d: path("M16 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.uk0rveqaj) {
  d: path("M4 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.zvg3vyivl) {
  d: path("M8 7h8");
}

</style>
