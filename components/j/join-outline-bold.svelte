<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="x5-v1c34k"/><path class="r1giuh9in"/><path class="l517yxbln"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:join-outline-bold" {...props}></Icon>
<style>
:global(.l517yxbln) {
  d: path("M12 9v6");
}

:global(.r1giuh9in) {
  d: path("M10 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x5-v1c34k) {
  d: path("M2 12a6 6 0 1 0 12 0 6 6 0 1 0 -12 0");
}

</style>
