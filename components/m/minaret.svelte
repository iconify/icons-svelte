<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="w-i-r6wac"/><path class="q6c4nebpj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:minaret" {...props}></Icon>
<style>
:global(.q6c4nebpj) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19.5v-3");
}

:global(.w-i-r6wac) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75V4.5m0 0c1.6 1.1 2.5 2.4 2.5 4h-5c0-1.6.9-2.9 2.5-4m-1.25 4h2.5q.5 0 .5.5v2.5q0 .5.5.5H15q.5 0 .5.5v.75q0 .5-.37.5q-.38 0-.33.5l.65 6.5q.05.5-.45.5H9q-.5 0-.45-.5l.65-6.5q.05-.5-.32-.5q-.38 0-.38-.5v-.75q0-.5.5-.5h.75q.5 0 .5-.5V9q0-.5.5-.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
