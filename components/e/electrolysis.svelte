<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ksm760gkm"/><path class="gc30fbn7i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:electrolysis" {...props}></Icon>
<style>
:global(.gc30fbn7i) {
  d: path("M10.75 15a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

:global(.ksm760gkm) {
  d: path("M3.5 6v13.5a2 2 0 0 0 2 2h13a2 2 0 0 0 2-2V6M8 2.5V17m8-14.5V17M3.5 10h17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
