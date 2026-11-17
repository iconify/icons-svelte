<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dc4zz8uqj"/><path class="ycel9wb0i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:battery-off-duocolor-round" {...props}></Icon>
<style>
:global(.dc4zz8uqj) {
  stroke-opacity: 0.4;
  d: path("M21 10v4M2 2l20 20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ycel9wb0i) {
  d: path("M16.562 16.562c-.455.278-.99.438-1.562.438H6a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3h1m6 0h2a3 3 0 0 1 3 3v2");
}

</style>
