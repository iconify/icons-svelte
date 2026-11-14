<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bn3wepw5b"/><path class="fm538_bxo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bandage-roll" {...props}></Icon>
<style>
:global(.bn3wepw5b) {
  d: path("M3 10a4 6.5 0 1 0 8 0a4 6.5 0 1 0-8 0Zm4-6.5h8.5");
}

:global(.fm538_bxo) {
  d: path("M15.5 3.5c2.25 0 4 3 4 6.5s-1.75 6.5-4 6.5H7M5.5 10a1.5 2.5 0 1 0 3 0a1.5 2.5 0 1 0-3 0Zm6-6.5v13m.5 0c2 2 4 .5 6 2.5c1.5 1.5 2.5 1.5 3.5 1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
