<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="enuudfbdr"/><path class="rft1pr_qz"/><path class="d6fbly8nu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:photo-spot" {...props}></Icon>
<style>
:global(.d6fbly8nu) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 7.25h.01");
}

:global(.enuudfbdr) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 11.75H6l.75-1.5h2l.75 1.5h1.25a2 2 0 0 1 2 2v5.5a2 2 0 0 1-2 2h-6a2 2 0 0 1-2-2v-5.5a2 2 0 0 1 2-2");
}

:global(.rft1pr_qz) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 14.75a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 1 0 0-3.5m10-2.25c-2-1.75-3.5-3.5-3.5-5.25a3.5 3.5 0 0 1 7 0c0 1.75-1.5 3.5-3.5 5.25");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
