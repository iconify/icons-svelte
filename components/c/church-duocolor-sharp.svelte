<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ohdwadw8m"/><path class="d5_18n1qg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:church-duocolor-sharp" {...props}></Icon>
<style>
:global(.d5_18n1qg) {
  d: path("M8 21V11l4-4l4 4v10m-8-8l-4 2v6h16v-6l-4-2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ohdwadw8m) {
  stroke-opacity: 0.4;
  d: path("M12 3v4m-2-2h4");
}

</style>
