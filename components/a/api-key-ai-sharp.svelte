<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="nr14crr6d"/><path class="brz32spoq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:api-key-ai-sharp" {...props}></Icon>
<style>
:global(.brz32spoq) {
  d: path("m11.3 12.7l8.45-8.45M17 7l2.5 2.5m.25-5.25l1.5 1.5M7.75 13.5l.33 2.42l2.42.33l-2.42.33L7.75 19l-.33-2.42L5 16.25l2.42-.33z");
}

:global(.nr14crr6d) {
  cx: 7.75px;
  cy: 16.25px;
  r: 5px;
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
