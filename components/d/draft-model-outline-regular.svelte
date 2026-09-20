<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tgd916uxo"/><path class="ebby1xbgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:draft-model-outline-regular" {...props}></Icon>
<style>
:global(.ebby1xbgn) {
  d: path("M16.5 6.5 22 12l-5.5 5.5L11 12Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tgd916uxo) {
  d: path("M5 9.5 7.5 12 5 14.5 2.5 12Z");
}

</style>
