<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o-hpvjb2b"/><path class="fr9vmkbmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:egg-sharp" {...props}></Icon>
<style>
:global(.fr9vmkbmk) {
  d: path("M8.5 14v-2.75L10 9");
}

:global(.o-hpvjb2b) {
  d: path("M12 2.75c-4 0-7 6.25-7 11a7 7 0 0 0 14 0c0-4.75-3-11-7-11Z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
