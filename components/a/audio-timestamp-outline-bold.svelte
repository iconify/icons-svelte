<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jq9hovbrs"/><path class="yomctlb4k"/><path class="r1ix196dy"/><path class="lit20acsf"/><path class="u41hfsjfh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:audio-timestamp-outline-bold" {...props}></Icon>
<style>
:global(.jq9hovbrs) {
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

:global(.lit20acsf) {
  d: path("M12 7.5v3");
}

:global(.r1ix196dy) {
  d: path("M9 10.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.u41hfsjfh) {
  d: path("M12 10.5h2.5");
}

:global(.yomctlb4k) {
  d: path("M7 17v4l4 -4");
}

</style>
