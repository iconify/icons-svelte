<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="n9lim1b5i"/><path class="mgf3jubms"/><path class="hyp8f8r9i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:captain-hat" {...props}></Icon>
<style>
:global(.hyp8f8r9i) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 17.5h13.5l-.6 1.6c-.35.85-1.2 1.4-2.1 1.4h-7.9c-.9 0-1.75-.55-2.1-1.4Z");
}

:global(.mgf3jubms) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8.25h.01");
}

:global(.n9lim1b5i) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 9.75C3 7.25 7 5 12 5s9 2.25 9 4.75c0 1.25-1 2-2.25 2.25v2.5H5.25V12C4 11.75 3 11 3 9.75M5.25 12h13.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
