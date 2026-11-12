<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pk9vkxkrw"/><path class="rxbx2dbkd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:credit-card-clock-corner-duotone-round" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.pk9vkxkrw) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M22 9H10v10a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V9a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5");
}

:global(.rxbx2dbkd) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 9a4 4 0 0 0-4-4H7a4 4 0 0 0-4 4v6a4 4 0 0 0 4 4h2M3 9h18m-9 8a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

</style>
