<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rpk9jeb_i"/><path class="b80eh0awx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folders-duocolor-sharp" {...props}></Icon>
<style>
:global(.b80eh0awx) {
  d: path("M10 11h7v10H3V9h5z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rpk9jeb_i) {
  stroke-opacity: 0.4;
  d: path("M7 5V3h5l2 2m0 0h7v10");
}

</style>
