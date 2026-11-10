<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ger4r73nt"/><path class="s5fw9zbva"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:align-vertical-space-around-sharp-two-tone" {...props}></Icon>
<style>
:global(.ger4r73nt) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 21H1V19H23V21ZM17 8C17.552 8 18 8.448 18 9V15C18 15.552 17.552 16 17 16H7C6.448 16 6 15.552 6 15V9C6 8.448 6.448 8 7 8H17ZM23 5H1V3H23V5Z");
  stroke: none;
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s5fw9zbva) {
  d: path("M23 20H1M23 4H1M17 9H7V12V15H17V12V9Z");
}

</style>
