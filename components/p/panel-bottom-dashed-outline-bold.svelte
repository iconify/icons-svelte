<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="n48w5yb-p"/><path class="dx4l09mjo"/><path class="duxnt0uao"/><path class="hr2hxb3wp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:panel-bottom-dashed-outline-bold" {...props}></Icon>
<style>
:global(.duxnt0uao) {
  d: path("M10.5 15h3");
}

:global(.dx4l09mjo) {
  d: path("M3.5 15h3");
}

:global(.hr2hxb3wp) {
  d: path("M17.5 15h3");
}

:global(.n48w5yb-p) {
  d: path("M14 4h5a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
