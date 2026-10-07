<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="h0eqbkbhb"/><path class="te6oycqze"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:a-arrow-down-sharp-duotone" {...props}></Icon>
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

:global(.te6oycqze) {
  d: path("M19 8L19 19M15.7071 15.7071L19 19L22.2929 15.7071");
}

</style>
