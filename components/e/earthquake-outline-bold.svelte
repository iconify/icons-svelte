<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nz19jcivh"/><path class="ov7kkt0lo"/><path class="vxy4ztabh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:earthquake-outline-bold" {...props}></Icon>
<style>
:global(.nz19jcivh) {
  d: path("M2 10h4l3 -3 3 3 3 -3 3 3h4");
}

:global(.ov7kkt0lo) {
  d: path("m8 17 4 4 4 -4");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.vxy4ztabh) {
  d: path("M4 14h16");
}

</style>
