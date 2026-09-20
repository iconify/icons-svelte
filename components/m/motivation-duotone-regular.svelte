<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w-p54wt7w"/><path class="v20aanbzl"/><path class="so5p-db7p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:motivation-duotone-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.so5p-db7p) {
  d: path("M7 12h3l3 -3V5h2.5v5H19v10H7Z");
}

:global(.v20aanbzl) {
  d: path("M7 12H3v8h4");
}

:global(.w-p54wt7w) {
  fill: currentColor;
  d: path("M7 12h3l3 -3V5h2.5v5H19v10H7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
