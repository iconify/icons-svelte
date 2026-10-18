<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tjgt7cc8v"/><path class="l9jud4mun"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-checks-sharp-two-tone" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.l9jud4mun) {
  d: path("M1.7071 6.7071L4 9L8.2929 4.7071M1.7071 16.7071L4 19L8.2929 14.7071");
}

:global(.tjgt7cc8v) {
  stroke-opacity: 0.4;
  d: path("M11 7L23 7M11 17L23 17");
}

</style>
