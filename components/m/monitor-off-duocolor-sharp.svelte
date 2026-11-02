<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q76_okbsb"/><path class="kfe5rwbik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:monitor-off-duocolor-sharp" {...props}></Icon>
<style>
:global(.kfe5rwbik) {
  d: path("M18 17H4V4h1m6 0h9v9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q76_okbsb) {
  stroke-opacity: 0.4;
  d: path("M9 20h6M3 2l19 19");
}

</style>
