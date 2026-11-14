<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e2dsidb5k"/><path class="m55p2dvpl"/><path class="j3lws1h8q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:loyalty-keyring-tag" {...props}></Icon>
<style>
:global(.e2dsidb5k) {
  d: path("M10 9h10.5a1 1 0 0 1 1 1v10.5a1 1 0 0 1-1 1H10a1 1 0 0 1-1-1V10a1 1 0 0 1 1-1ZM2.5 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm5.25 2.25l2 2");
}

:global(.j3lws1h8q) {
  fill: currentColor;
  d: path("m15.75 12.25l1.029 2.334l2.537.257l-1.902 1.7l.54 2.493l-2.204-1.284l-2.204 1.284l.54-2.493l-1.902-1.7l2.537-.257Z");
}

:global(.m55p2dvpl) {
  d: path("M11 11.75a.75.75 0 1 0 1.5 0a.75.75 0 1 0-1.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
