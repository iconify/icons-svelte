<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qm_3ftbkj"/><path class="ukk5i1bfk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:card-image" {...props}></Icon>
<style>
:global(.qm_3ftbkj) {
  d: path("M3 3.5h18v17H3ZM3 14h18");
}

:global(.ukk5i1bfk) {
  d: path("m6 11l3-3l3 3m4-3.5h.01M6.5 17.25H12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
