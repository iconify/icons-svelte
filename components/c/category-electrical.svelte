<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n243trl7h"/><path class="uxnbunbfc"/><path class="kxe0zpavv"/><path class="ligsbjwqw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:category-electrical" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kxe0zpavv) {
  fill: currentColor;
  d: path("M8.5 12h7v3a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8.5 15Z");
}

:global(.ligsbjwqw) {
  d: path("M12 4.75h.01M12 19.25h.01");
}

:global(.n243trl7h) {
  d: path("M8.875 2h6.25A4.375 4.375 0 0 1 19.5 6.375v11.25A4.375 4.375 0 0 1 15.125 22h-6.25A4.375 4.375 0 0 1 4.5 17.625V6.375A4.375 4.375 0 0 1 8.875 2");
}

:global(.uxnbunbfc) {
  d: path("M11.125 7.5h1.75a2.625 2.625 0 0 1 2.625 2.625v3.75a2.625 2.625 0 0 1-2.625 2.625h-1.75A2.625 2.625 0 0 1 8.5 13.875v-3.75A2.625 2.625 0 0 1 11.125 7.5M8.5 12h7");
}

</style>
