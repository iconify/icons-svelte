<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mf-kq8bqj"/><path class="yxm9t6wwy"/><path class="tc2m7movw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:kiosk-news" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mf-kq8bqj) {
  d: path("m3.585 6.329l1-2A1.5 1.5 0 0 1 5.927 3.5h12.146a1.5 1.5 0 0 1 1.342.829l1 2A1.5 1.5 0 0 1 19.073 8.5H4.927a1.5 1.5 0 0 1-1.342-2.171");
}

:global(.tc2m7movw) {
  d: path("M10 11.25h4a1.5 1.5 0 0 1 1.5 1.5V14a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 8.5 14v-1.25a1.5 1.5 0 0 1 1.5-1.5m2 0v4.25");
}

:global(.yxm9t6wwy) {
  d: path("M4.5 8.5v13h15v-13m-15 7h15");
}

</style>
