<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bjghabb4y"/><path class="qflyskbix"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:eye-low-vision" {...props}></Icon>
<style>
:global(.bjghabb4y) {
  d: path("M2.5 12C5 7.5 8.25 5.5 12 5.5s7 2 9.5 6.5M4 15l2.5 1.75m3.5 1.5h4m3.5-1.5L20 15");
}

:global(.qflyskbix) {
  d: path("M9.25 11.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
