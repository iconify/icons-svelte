<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d_pdzpb1w"/><path class="be9rdrb3n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:arrow-curve-down-left" {...props}></Icon>
<style>
:global(.be9rdrb3n) {
  d: path("M13 21H8v-5");
}

:global(.d_pdzpb1w) {
  d: path("M16 3v7c0 2-.75 3.75-2 5l-6 6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
