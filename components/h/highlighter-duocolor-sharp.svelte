<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yhebvhb6f"/><path class="c84pb3ebf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:highlighter-duocolor-sharp" {...props}></Icon>
<style>
:global(.c84pb3ebf) {
  d: path("m7 11l7-7l6 6l-7 7z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.yhebvhb6f) {
  stroke-opacity: 0.4;
  d: path("m8 12l-5 5v3h5l4-4");
}

</style>
