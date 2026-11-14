<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="l1tv0xafw"/><path class="e3oatubaj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:e-prescription" {...props}></Icon>
<style>
:global(.e3oatubaj) {
  d: path("M9 17.25v-7.5h2.25c1.25 0 2 .75 2 2s-.75 2-2 2H9m2.25 0l3.25 3.75m0-3.25l-2.75 3.25");
}

:global(.l1tv0xafw) {
  d: path("M6 2.5h12v19H6ZM10.5 5h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
