<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k-9q2cbvs"/><path class="ju4i6gx3w"/><path class="dtjohzbue"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:fold-clothes-outline-bold" {...props}></Icon>
<style>
:global(.dtjohzbue) {
  d: path("M5 17h14v3H5Z");
}

:global(.ju4i6gx3w) {
  d: path("M7 11h10v3H7Z");
}

:global(.k-9q2cbvs) {
  d: path("M5 5h14v3H5Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
