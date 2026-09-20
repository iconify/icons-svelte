<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mqtixbwqo"/><path class="yam3-1b2z"/><path class="mei2sobow"/><path class="xmopbdc-t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:coffee-table-outline-regular" {...props}></Icon>
<style>
:global(.mei2sobow) {
  d: path("M19 8v12");
}

:global(.mqtixbwqo) {
  d: path("M2 8h20");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xmopbdc-t) {
  d: path("M5 15h14");
}

:global(.yam3-1b2z) {
  d: path("M5 8v12");
}

</style>
