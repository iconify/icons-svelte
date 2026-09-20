<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ymw3aibdo"/><path class="aq5i5tblx"/><path class="p83l94bht"/><path class="cm0vclbrz"/><path class="j66gzwnbv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:family-tree-outline-regular" {...props}></Icon>
<style>
:global(.aq5i5tblx) {
  d: path("M4 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.cm0vclbrz) {
  d: path("M12 7v4H6v4");
}

:global(.j66gzwnbv) {
  d: path("M12 11h6v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p83l94bht) {
  d: path("M16 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ymw3aibdo) {
  d: path("M10 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
