<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="c8hmcy6ke"/><path class="hn0465b8v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:infusion-chair" {...props}></Icon>
<style>
:global(.c8hmcy6ke) {
  d: path("m3 6l3 8h7.5l3 4.5M5.75 10.75h4.75M7.5 14v5.5M12 14v5.5m-6.5 0H14m6 2v-18h-3");
}

:global(.hn0465b8v) {
  d: path("M15.25 5.5h3.5v5h-3.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
