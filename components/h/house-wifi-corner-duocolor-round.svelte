<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wszhf93xl"/><path class="aay9q5bec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-wifi-corner-duocolor-round" {...props}></Icon>
<style>
:global(.aay9q5bec) {
  d: path("M8 21a4 4 0 0 1-4-4v-5.185a4 4 0 0 1 1.366-3.01l4-3.5a4 4 0 0 1 5.268 0L17.714 8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wszhf93xl) {
  stroke-opacity: 0.4;
  d: path("M15 18a2.83 2.83 0 0 1 4 0m-6-3a6.4 6.4 0 0 1 8 0m-4 6h.01");
}

</style>
