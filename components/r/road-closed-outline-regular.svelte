<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r8vbx7bdh"/><path class="z475fobui"/><path class="r182r524c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:road-closed-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r182r524c) {
  d: path("M7 9h10");
}

:global(.r8vbx7bdh) {
  d: path("M5 9a7 7 0 1 0 14 0A7 7 0 1 0 5 9");
}

:global(.z475fobui) {
  d: path("M12 16v6");
}

</style>
