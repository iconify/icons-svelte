<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qzuim9b1a"/><path class="bp7trtb7b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bacon-pack" {...props}></Icon>
<style>
:global(.bp7trtb7b) {
  d: path("M6.5 16c2.5-1.5 1-6.5 4-8m-.25 8c2.5-1.5 1-6.5 4-8M14 16c2.5-1.5 1-6.5 4-8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.qzuim9b1a) {
  d: path("M4 5h16l1.5 1.75L20 8.5l1.5 1.75L20 12l1.5 1.75L20 15.5l1.5 1.75L20 19H4l-1.5-1.75L4 15.5l-1.5-1.75L4 12l-1.5-1.75L4 8.5L2.5 6.75Z");
}

</style>
