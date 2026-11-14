<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r4nmxrb0m"/><path class="m9r7aqb6z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chicken-run" {...props}></Icon>
<style>
:global(.m9r7aqb6z) {
  d: path("M6 20v-2.5a1.5 1.5 0 0 1 3 0V20");
}

:global(.r4nmxrb0m) {
  d: path("m3 10l4.5-5.5L12 10v10H3Zm9 2.5h9m-9 4h9m-4.5-7V20M21 9.5V20");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
