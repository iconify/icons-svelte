<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="iyx_wfbrs"/><path class="wng135bew"/><path class="sosl8ibaa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:evil-eye-charm" {...props}></Icon>
<style>
:global(.iyx_wfbrs) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v4.9m-9.25 5.6C6 6 18 6 21.25 13.5C18 21 6 21 2.75 13.5");
}

:global(.sosl8ibaa) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 13.5h.01");
}

:global(.wng135bew) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 13.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
