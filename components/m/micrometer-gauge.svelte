<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="brzn_ippx"/><path class="blh_albhr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:micrometer-gauge" {...props}></Icon>
<style>
:global(.blh_albhr) {
  d: path("M13 5.5h8v5h-8Zm4 0v5");
}

:global(.brzn_ippx) {
  d: path("M3.5 5.5V13A5.5 5.5 0 0 0 9 18.5h6v-8M6.5 8H13");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
