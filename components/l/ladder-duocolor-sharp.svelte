<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="clclfqblq"/><path class="gms1kji-y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ladder-duocolor-sharp" {...props}></Icon>
<style>
:global(.clclfqblq) {
  stroke-opacity: 0.4;
  d: path("M8 7h8m-8 5h8m-8 5h8");
}

:global(.gms1kji-y) {
  d: path("M8 3v18m8-18v18");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
