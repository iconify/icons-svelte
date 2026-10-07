<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="h0eqbkbhb"/><path class="r-utvqa8d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:a-arrow-up-sharp-duotone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.h0eqbkbhb) {
  stroke-opacity: 0.4;
  d: path("M1.9417 19.6637L7.1788 5L12.4158 19.6637M3.9645 14L10.3931 14");
}

:global(.r-utvqa8d) {
  d: path("M19 20L19 9M15.7071 12.2929L19 9L22.2929 12.2929");
}

</style>
