<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lwk28k3zq"/><path class="skbifdbcx"/><path class="dfl4nkbui"/><path class="m8uexfcos"/><path class="lc5qczbkz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-report-duotone-bold" {...props}></Icon>
<style>
:global(.dfl4nkbui) {
  d: path("M12 16a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

:global(.lc5qczbkz) {
  d: path("M16.5 16H21");
}

:global(.lwk28k3zq) {
  fill: currentColor;
  d: path("M12 16a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.m8uexfcos) {
  d: path("M16.5 11.5V16");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.skbifdbcx) {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

</style>
