<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ar4p7fb_d"/><path class="qk302m6ft"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:octagon-info-duocolor-sharp" {...props}></Icon>
<style>
:global(.ar4p7fb_d) {
  stroke-opacity: 0.4;
  d: path("M12 8h.01M12 11v5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qk302m6ft) {
  d: path("M12 3h4l5 5v8l-5 5H8l-5-5V8l5-5z");
}

</style>
