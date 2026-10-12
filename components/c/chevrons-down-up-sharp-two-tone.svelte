<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="o019cd_5e"/><path class="p5pdrebjg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:chevrons-down-up-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o019cd_5e) {
  stroke-opacity: 0.4;
  d: path("M6.7071 3.7071L12 9L17.2929 3.7071");
}

:global(.p5pdrebjg) {
  d: path("M6.7071 20.2929L12 15L17.2929 20.2929");
}

</style>
