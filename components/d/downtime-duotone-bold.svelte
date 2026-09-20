<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bjdq34bim"/><path class="hen7e0d7r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:downtime-duotone-bold" {...props}></Icon>
<style>
:global(.bjdq34bim) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h4V6h4v12h4v-6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.hen7e0d7r) {
  d: path("M3 12h4V6h4v12h4v-6h6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
