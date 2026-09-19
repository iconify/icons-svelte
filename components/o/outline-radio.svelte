<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wh37oylvy"/><circle class="o7zd1cb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-radio" {...props}></Icon>
<style>
:global(.o7zd1cb4l) {
  cx: 8px;
  cy: 16.48px;
  r: 2.5px;
  fill: currentColor;
}

:global(.wh37oylvy) {
  fill: currentColor;
  d: path("M20 6H8.3l8.26-3.34L15.88 1L3.24 6.15C2.51 6.43 2 7.17 2 8v12a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V8c0-1.11-.89-2-2-2m0 2v3h-2V9h-2v2H4V8zM4 20v-7h16v7z");
}

</style>
