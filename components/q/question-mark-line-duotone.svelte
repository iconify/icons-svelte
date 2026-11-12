<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wr5b81bpi"/><path class="azdzsac_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:question-mark-line-duotone" {...props}></Icon>
<style>
:global(.azdzsac_a) {
  stroke-linejoin: round;
  d: path("M12 22H12.0001");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wr5b81bpi) {
  d: path("M8 6.2969C8 3.92379 9.95877 2 12.375 2C14.7913 2 16.7501 3.92379 16.7501 6.2969C16.7501 7.87231 15.8868 9.2497 14.5996 9.99769C13.4905 10.6422 12.375 11.6198 12.375 12.8855V15.7501");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
