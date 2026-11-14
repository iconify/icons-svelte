<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f5yulux_f"/><path class="s8nb6fbws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:flag-penalty-number" {...props}></Icon>
<style>
:global(.f5yulux_f) {
  d: path("M4.5 2.5v19M4.5 4H19a1 1 0 0 1 1 1v9a1 1 0 0 1-1 1H4.5");
}

:global(.s8nb6fbws) {
  d: path("M9 7h6.5v5H9Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
