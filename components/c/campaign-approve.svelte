<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qxn4prbzl"/><path class="chqj8zbvs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:campaign-approve" {...props}></Icon>
<style>
:global(.chqj8zbvs) {
  d: path("M8.5 2.5h7V6h-7Zm0 11L11 16l4.5-4.5");
}

:global(.qxn4prbzl) {
  d: path("M8.5 4.25H7a2.5 2.5 0 0 0-2.5 2.5V19A2.5 2.5 0 0 0 7 21.5h10a2.5 2.5 0 0 0 2.5-2.5V6.75a2.5 2.5 0 0 0-2.5-2.5h-1.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
