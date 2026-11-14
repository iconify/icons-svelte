<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xzs7lnbgq"/><path class="h1ui4cb_o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:press-gallery" {...props}></Icon>
<style>
:global(.h1ui4cb_o) {
  d: path("M9.5 8.5h7V12M8 21.5h8M12 16v5.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xzs7lnbgq) {
  d: path("M4.5 5a2.5 2.5 0 0 1 5 0v7h8a2 2 0 0 1 0 4h-11a2 2 0 0 1-2-2Z");
}

</style>
