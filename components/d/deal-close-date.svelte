<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="s_fuuhzob"/><path class="dm_wopyrf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:deal-close-date" {...props}></Icon>
<style>
:global(.dm_wopyrf) {
  d: path("M16.5 17.5v-1a1.5 1.5 0 0 1 3 0v1");
}

:global(.s_fuuhzob) {
  d: path("M12.2 20.5H2.5V4h17v8.5M2.5 9h17m-12-6.5V6m7-3.5V6m.5 11.5h6v4h-6Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
