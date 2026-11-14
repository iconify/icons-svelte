<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ce0dzhbee"/><path class="fsgcxn_qa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fossil-leaf" {...props}></Icon>
<style>
:global(.ce0dzhbee) {
  d: path("M3.5 8L8 4h10.5L21 9v8l-4 3.5H6L3 16Z");
}

:global(.fsgcxn_qa) {
  d: path("M7.5 16.5c0-6.5 3-9 9.5-9c0 6.5-3 9-9.5 9Zm0 0l6.75-6.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
