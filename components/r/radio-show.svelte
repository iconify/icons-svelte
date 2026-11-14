<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tzqgw21wh"/><path class="hq5oouuxz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:radio-show" {...props}></Icon>
<style>
:global(.hq5oouuxz) {
  d: path("M12.5 14.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm-6.5-2h3m-3 4h3");
}

:global(.tzqgw21wh) {
  d: path("M2.5 8h19v13h-19ZM7 8l10.5-5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
