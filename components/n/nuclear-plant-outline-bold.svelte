<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nk2bhslfp"/><path class="morp7_b7k"/><path class="dj0q8oblb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:nuclear-plant-outline-bold" {...props}></Icon>
<style>
:global(.dj0q8oblb) {
  d: path("M12 2a2.5 2.5 0 0 1 0 5");
}

:global(.morp7_b7k) {
  d: path("M12 12a2.5 2.5 0 0 1 0 -5");
}

:global(.nk2bhslfp) {
  d: path("m7 20 2 -2V9h6v9l2 2Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
