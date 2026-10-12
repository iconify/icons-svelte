<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="gcrfhow0n"/><path class="h06bnrbuh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:peanut" {...props}></Icon>
<style>
:global(.gcrfhow0n) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75c2.5 0 4.5 2 4.5 4.5c0 1.5-.6 2.6-1.25 3.6c-.35.55-.35 1.1.1 1.6c1.2 1.2 2.4 2.5 2.4 4.55c0 2.4-2.5 4.25-5.75 4.25S6.25 19.4 6.25 17c0-2.05 1.2-3.35 2.4-4.55c.45-.5.45-1.05.1-1.6c-.65-1-1.25-2.1-1.25-3.6c0-2.5 2-4.5 4.5-4.5");
}

:global(.h06bnrbuh) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.75 6.5h.01m2.49 2.25h.01m-3.01 7.5h.01m3.49 1.5h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
