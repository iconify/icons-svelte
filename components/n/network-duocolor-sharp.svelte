<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yoptg-bym"/><path class="eqy9g_trh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:network-duocolor-sharp" {...props}></Icon>
<style>
:global(.eqy9g_trh) {
  d: path("M9 3h6v5H9ZM3 16h6v5H3Zm12 0h6v5h-6Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yoptg-bym) {
  stroke-opacity: 0.4;
  d: path("M12 8v4m-6 4v-4h12v4");
}

</style>
