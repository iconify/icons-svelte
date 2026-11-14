<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mih382b2v"/><path class="nmhnie-7b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:home-alarm-discount" {...props}></Icon>
<style>
:global(.mih382b2v) {
  d: path("M12.523 19.5H2.5v-10l8.5-7l8.5 7v3.077");
}

:global(.nmhnie-7b) {
  d: path("M6 15h6l-1-1.25v-2a2 2 0 0 0-4 0v2Zm8.75 6.25l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
