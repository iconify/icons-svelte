<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nyxvsabjb"/><path class="kgjd6kwzl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:layout-template-duocolor-sharp" {...props}></Icon>
<style>
:global(.kgjd6kwzl) {
  d: path("M4 13h8v7H4Zm12 0h4v7h-4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nyxvsabjb) {
  stroke-opacity: 0.4;
  d: path("M4 4h16v5H4Z");
}

</style>
