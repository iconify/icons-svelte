<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hcyd1clvm"/><path class="xbkq17beg"/><path class="bprf6vbci"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:policy-cooling-off" {...props}></Icon>
<style>
:global(.bprf6vbci) {
  d: path("m10.5 11.75l-2 2l2 2");
}

:global(.hcyd1clvm) {
  d: path("M3.5 4.5h17v17h-17Zm0 4.5h17M8 2.5V6m8-3.5V6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.xbkq17beg) {
  d: path("M8.5 13.75H14a2.25 2.25 0 0 1 0 4.5h-3.5");
}

</style>
