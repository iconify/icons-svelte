<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m_m6c4t8g"/><path class="va0rjdbnq"/><path class="hcn7bdzwu"/><path class="dky0phbxv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:composite-key-outline-regular" {...props}></Icon>
<style>
:global(.dky0phbxv) {
  d: path("M19 11v7");
}

:global(.hcn7bdzwu) {
  d: path("M15 11v7");
}

:global(.m_m6c4t8g) {
  d: path("M2 11a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.va0rjdbnq) {
  d: path("M8 11h12");
}

</style>
