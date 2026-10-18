<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="auvtk9bkr"/><path class="x9obmne9u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-indent-decrease-duotone" {...props}></Icon>
<style>
:global(.auvtk9bkr) {
  stroke-opacity: 0.4;
  d: path("M8 12L2 12M5 9L2 12L5 15");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x9obmne9u) {
  d: path("M12 6L22 6M12 12L22 12M12 18L22 18");
}

</style>
