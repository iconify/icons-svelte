<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="srzgk7jml"/><path class="ic_pehd5a"/><path class="fbw2ldgtv"/><path class="xsyfe-byx"/><path class="mvo4nxq3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:car-dashboard-outline-regular" {...props}></Icon>
<style>
:global(.fbw2ldgtv) {
  d: path("M12 10v7");
}

:global(.ic_pehd5a) {
  d: path("M3 17h18");
}

:global(.mvo4nxq3c) {
  d: path("M16 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.srzgk7jml) {
  d: path("M3 17a9 9 0 0 1 18 0");
}

:global(.xsyfe-byx) {
  d: path("M6 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
