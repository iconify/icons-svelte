<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n09nomjwg"/><path class="qp8kb8bwr"/><path class="z4xd2x6yx"/><path class="e7q8l6x6g"/><path class="osdsz4bam"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:configmap-outline-bold" {...props}></Icon>
<style>
:global(.e7q8l6x6g) {
  d: path("M6 14h5");
}

:global(.n09nomjwg) {
  d: path("M15 6h3a3 3 0 0 1 3 3v6a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V9a3 3 0 0 1 3 -3h3");
}

:global(.osdsz4bam) {
  d: path("M13 14h5");
}

:global(.qp8kb8bwr) {
  d: path("M6 10h5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.z4xd2x6yx) {
  d: path("M13 10h5");
}

</style>
