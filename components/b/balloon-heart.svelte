<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="fh4xkdftj"/><path class="aez1u0y-y"/><path class="pzhmyob9w"/><path class="byx-nejhk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:balloon-heart" {...props}></Icon>
<style>
:global(.aez1u0y-y) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 8a2 2 0 0 1 1.75-2");
}

:global(.byx-nejhk) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 19q-1.5 1.125 0 2.25");
}

:global(.fh4xkdftj) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 16.25c-4.5-3-7.75-5.75-7.75-9.25A4 4 0 0 1 12 5.5A4 4 0 0 1 19.75 7c0 3.5-3.25 6.25-7.75 9.25");
}

:global(.pzhmyob9w) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 18h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
