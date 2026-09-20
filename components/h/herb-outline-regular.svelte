<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mnwr0qhch"/><path class="hc0aulbwc"/><path class="fmqqksbgb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:herb-outline-regular" {...props}></Icon>
<style>
:global(.fmqqksbgb) {
  d: path("M12 14c4 0 6 -2 6 -5 -4 0 -6 2 -6 5");
}

:global(.hc0aulbwc) {
  d: path("M12 9C8 9 6 7 6 4c4 0 6 2 6 5");
}

:global(.mnwr0qhch) {
  d: path("M12 4v17");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
