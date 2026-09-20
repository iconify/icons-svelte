<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wv6md6qod"/><path class="slki1jkee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:favorite-bookmark-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.slki1jkee) {
  d: path("M8 10a2 2 0 0 1 4 0 2 2 0 0 1 4 0l-4 4Z");
}

:global(.wv6md6qod) {
  d: path("M15 3h3v18l-6 -6 -6 6V3h3");
}

</style>
