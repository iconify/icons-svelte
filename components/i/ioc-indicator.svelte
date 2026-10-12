<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="h60ap67ws"/><path class="k0szy4bby"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ioc-indicator" {...props}></Icon>
<style>
:global(.h60ap67ws) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 21.25V2.75m0 .75h13.5l-2.75 4.25L18.5 12H5Zm5.5 2v2");
}

:global(.k0szy4bby) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 10h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
