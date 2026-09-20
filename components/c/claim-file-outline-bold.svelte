<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="t9gnp4b0n"/><path class="ae-e09b3w"/><path class="ohhz_s35v"/><path class="yb0sj-xar"/><path class="fobf5jwcl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:claim-file-outline-bold" {...props}></Icon>
<style>
:global(.ae-e09b3w) {
  d: path("M3 12h18");
}

:global(.fobf5jwcl) {
  d: path("m9.5 10 5 -5");
}

:global(.ohhz_s35v) {
  d: path("M12 12v6");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.t9gnp4b0n) {
  d: path("M3 12a9 9 0 0 1 18 0");
}

:global(.yb0sj-xar) {
  d: path("M12 18a2 2 0 0 1 -4 0");
}

</style>
