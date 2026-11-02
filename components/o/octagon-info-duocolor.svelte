<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ar4p7fb_d"/><path class="fz9ry0b6m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:octagon-info-duocolor" {...props}></Icon>
<style>
:global(.ar4p7fb_d) {
  stroke-opacity: 0.4;
  d: path("M12 8h.01M12 11v5");
}

:global(.fz9ry0b6m) {
  d: path("M12 3h3c.64 0 1.36.36 2 1l3 3c.64.64 1 1.36 1 2v6c0 .64-.36 1.36-1 2l-3 3c-.64.64-1.36 1-2 1H9c-.64 0-1.36-.36-2-1l-3-3c-.64-.64-1-1.36-1-2V9c0-.64.36-1.36 1-2l3-3c.64-.64 1.36-1 2-1z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
