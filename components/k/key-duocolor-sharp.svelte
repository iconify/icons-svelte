<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o9v-03xhl"/><path class="ykdrq7mgm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:key-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o9v-03xhl) {
  stroke-opacity: 0.4;
  d: path("m16 8l2 2m1-5l2 2");
}

:global(.ykdrq7mgm) {
  d: path("m12 12l9-9M3 16a5 5 0 1 0 10 0a5 5 0 0 0-10 0");
}

</style>
