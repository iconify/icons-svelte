<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-47.52 24 24)" class="tsvo8l-uc"/><path class="actk2hqkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:emoji-flag-japan" {...props}></Icon>
<style>
:global(.actk2hqkm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 12.13v23.74c-2.459-.636-4.875-1.272-9.75-1.272c-8.478 0-11.022 2.543-19.5 2.543c-4.875 0-7.334-.636-9.75-1.271V12.13c2.416.636 4.875 1.272 9.75 1.272c8.478 0 11.022-2.543 19.5-2.543c4.875 0 7.291.636 9.75 1.271");
}

:global(.tsvo8l-uc) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 7.49px;
  ry: 6.28px;
}

</style>
