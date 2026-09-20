<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jd-uqebzu"/><path class="wuvisubmw"/><path class="q6q805_az"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:repository-outline-bold" {...props}></Icon>
<style>
:global(.jd-uqebzu) {
  d: path("M13.5 3H17a3 3 0 0 1 3 3v12a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V6a3 3 0 0 1 3 -3h3.5");
}

:global(.q6q805_az) {
  d: path("M12 3v7l2.5 -2.5L17 10V3");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.wuvisubmw) {
  d: path("M8 3v18");
}

</style>
