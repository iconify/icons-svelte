<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t7ek65bgo"/><path class="hp5g1ymeh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:new-build" {...props}></Icon>
<style>
:global(.hp5g1ymeh) {
  d: path("M6.5 21.5V18h3v3.5");
}

:global(.t7ek65bgo) {
  d: path("m3 15l5-4.5l5 4.5v6.5H3Zm15.5 6.5v-19m-14 3h17M8 5.5v2m8.5 14h4");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
