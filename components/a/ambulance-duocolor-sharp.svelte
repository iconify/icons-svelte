<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n7b50fb1f"/><path class="alqpcvbyk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ambulance-duocolor-sharp" {...props}></Icon>
<style>
:global(.alqpcvbyk) {
  d: path("M5 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-9-7h4M8 9v4");
}

:global(.n7b50fb1f) {
  stroke-opacity: 0.4;
  d: path("M5 18H3V5h10v13m0-10h4l4 4v6h-2M9 18h6m-2-6h7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
