<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w05p-xtrj"/><path class="ie42d9bfu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:letter-spacing-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ie42d9bfu) {
  d: path("M2 3L2 21M22 3L22 21");
}

:global(.w05p-xtrj) {
  stroke-opacity: 0.4;
  d: path("M6.928 18.6273L12 6L17.072 18.6273M9.188 13L14.812 13");
}

</style>
