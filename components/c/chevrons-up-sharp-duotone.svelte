<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p61phbjmj"/><path class="ouotnccue"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chevrons-up-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ouotnccue) {
  d: path("M6.7071 18.2929L12 13L17.2929 18.2929");
}

:global(.p61phbjmj) {
  stroke-opacity: 0.4;
  d: path("M6.7071 11.2929L12 6L17.2929 11.2929");
}

</style>
