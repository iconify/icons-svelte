<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n_4gpdb7w"/><path class="xst2h5svb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-dashed-play-three-quarter-duocolor-sharp" {...props}></Icon>
<style>
:global(.n_4gpdb7w) {
  stroke-opacity: 0.4;
  d: path("M10 8v8l6-4z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xst2h5svb) {
  d: path("M10.592 3.11a9 9 0 1 1-7.481 7.482M4.719 6.71a9 9 0 0 1 1.99-1.991");
}

</style>
