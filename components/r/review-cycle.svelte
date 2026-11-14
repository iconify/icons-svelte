<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="umawoe4ex"/><path class="kumr2hb2u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:review-cycle" {...props}></Icon>
<style>
:global(.kumr2hb2u) {
  d: path("M16.25 5.25h2.5v-2.5M12 7l1.323 3.18l3.432.275l-2.615 2.24l.799 3.35L12 14.25l-2.939 1.795l.799-3.35l-2.615-2.24l3.432-.275Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.umawoe4ex) {
  d: path("M21.176 9.541a9.5 9.5 0 1 1-2.458-4.259");
}

</style>
