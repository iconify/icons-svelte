<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zxl6wqb0d"/><path class="qpy5vjbdd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:devices-code-corner-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qpy5vjbdd) {
  d: path("M15 3h6v10h-6Zm-4 1H3v12h7");
}

:global(.zxl6wqb0d) {
  stroke-opacity: 0.4;
  d: path("m15 17l-2 2l2 2m4-4l2 2l-2 2");
}

</style>
