<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lt1qxne8j"/><path class="w7kvw9-1r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cable-car-alt-duocolor-sharp" {...props}></Icon>
<style>
:global(.lt1qxne8j) {
  stroke-opacity: 0.4;
  d: path("m4 9l16-4m-8 2v6m-2-9h.01M14 3h.01");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.w7kvw9-1r) {
  d: path("M4 13h16v8H4zm0 4h16M9 13v4m6-4v4");
}

</style>
