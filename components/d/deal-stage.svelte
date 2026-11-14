<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w_pw9eb1d"/><path class="o1o1z0zae"/><path class="g7n7brbxo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:deal-stage" {...props}></Icon>
<style>
:global(.g7n7brbxo) {
  d: path("M17 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM7 12h2.5m5 0H17");
}

:global(.o1o1z0zae) {
  fill: currentColor;
  d: path("M9.5 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.w_pw9eb1d) {
  d: path("M2 12a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
