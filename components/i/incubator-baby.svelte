<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="rw7yt_b9f"/><path class="iwnceybul"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:incubator-baby" {...props}></Icon>
<style>
:global(.iwnceybul) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 15.25h.01");
}

:global(.rw7yt_b9f) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 18.5v-5.25a7.75 7.75 0 0 1 15.5 0v5.25m-17 0h18.5");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
