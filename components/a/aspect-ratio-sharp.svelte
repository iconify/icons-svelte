<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="hmz588b6d"/><path class="twxvwlbnw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:aspect-ratio-sharp" {...props}></Icon>
<style>
:global(.hmz588b6d) {
  d: path("M2.75 5.25h18.5v13.5H2.75z");
}

:global(.twxvwlbnw) {
  d: path("M6.25 11.25v-2.5h2.5m9 4v2.5h-2.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
