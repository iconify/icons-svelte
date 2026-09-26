<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gbp5ycvai"/><path class="ah3kfl0kj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chevrons-left-right-duotone" {...props}></Icon>
<style>
:global(.ah3kfl0kj) {
  d: path("M15 7L20 12L15 17");
}

:global(.gbp5ycvai) {
  stroke-opacity: 0.4;
  d: path("M9 7L4 12L9 17");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
