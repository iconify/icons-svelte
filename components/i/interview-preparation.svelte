<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ipsqhx4hx"/><path class="km41f2g9r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:interview-preparation" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ipsqhx4hx) {
  d: path("M5.75 8.75a6.25 6.75 0 1 0 12.5 0a6.25 6.75 0 1 0-12.5 0");
}

:global(.km41f2g9r) {
  d: path("M12 15.5za1.25 1.25 0 0 1 1.25 1.25v3.5A1.25 1.25 0 0 1 12 21.5a1.25 1.25 0 0 1-1.25-1.25v-3.5A1.25 1.25 0 0 1 12 15.5M9.75 6.75h4.5a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1H11.5L10 12v-1.25h-.25a1 1 0 0 1-1-1v-2a1 1 0 0 1 1-1");
}

</style>
