<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="foylt9ial"/><path class="row4r_b0n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lane-arrow-right" {...props}></Icon>
<style>
:global(.foylt9ial) {
  d: path("M7 20v-8.5a3 3 0 0 1 3-3h9");
}

:global(.row4r_b0n) {
  d: path("M15.25 4.75L19 8.5l-3.75 3.75");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
