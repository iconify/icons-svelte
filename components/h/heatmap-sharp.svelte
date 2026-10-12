<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="zn0n03b0e"/><path class="in_yp6bue"/><path class="h5ugdc6tw"/><path class="ezm81yf6g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:heatmap-sharp" {...props}></Icon>
<style>
:global(.ezm81yf6g) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19.25h.01m7.24 0h.01");
}

:global(.h5ugdc6tw) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 17.25h2.75v4h-4v-4z");
}

:global(.in_yp6bue) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.25 12h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.zn0n03b0e) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h4v4h-4zm7.25 0h4v4h-4zm8.5 0h2.75v4h-4v-4zM2.75 10h4v4h-4zM10 10h4v4h-4z");
}

</style>
