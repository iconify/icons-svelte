<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m6trofguq"/><path class="a249dcbsw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:activity-ring-outline-bold" {...props}></Icon>
<style>
:global(.a249dcbsw) {
  d: path("M12 6.5A5.5 5.5 0 1 1 6.5 12");
}

:global(.m6trofguq) {
  d: path("M12 21a9 9 0 1 1 9 -9");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
