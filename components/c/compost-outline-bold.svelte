<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hlqoyz1hh"/><path class="jkuojibnm"/><path class="l517yxbln"/><path class="n8qem9biv"/><path class="h-2uoubai"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:compost-outline-bold" {...props}></Icon>
<style>
:global(.h-2uoubai) {
  d: path("M12 12c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

:global(.hlqoyz1hh) {
  d: path("M3 20a9 9 0 0 1 18 0");
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.l517yxbln) {
  d: path("M12 9v6");
}

:global(.n8qem9biv) {
  d: path("M6 12c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
