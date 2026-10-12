<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="mdswc-b6o"/><path class="y5n07bccj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:kilowatt-hour" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mdswc-b6o) {
  cx: 9px;
  cy: 9px;
  r: 6.25px;
}

:global(.y5n07bccj) {
  d: path("M9 5.75V9l2.25 1.5m7.37 1.71l-3.74 4.58q-.38.46.22.46h1.8q.6 0 .49.59l-.53 2.82q-.11.59.26.12l3.76-4.81q.37-.47-.23-.47h-1.8q-.6 0-.48-.59l.51-2.57q.12-.59-.26-.13");
}

</style>
