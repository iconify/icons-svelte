<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="v7dqcwgbe"/><path class="pl75u7wzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:comparison-period-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.pl75u7wzh) {
  d: path("m7 10 3 -3 3 3 3 -3 3 3");
}

:global(.r3faxubne) {
  d: path("M4 4v16");
}

:global(.v7dqcwgbe) {
  d: path("m7 15 3 -3 3 3 3 -3 3 3");
}

</style>
