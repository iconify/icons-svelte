<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k-747lbuo"/><path class="fpc2nnn1w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:person-jumping" {...props}></Icon>
<style>
:global(.fpc2nnn1w) {
  d: path("M4 4.5L8.5 10h7L20 4.5M12 10v5l-5.5 6m5.5-6l5.5 6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k-747lbuo) {
  d: path("M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
