<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jtrmczbpr"/><path class="f-x5yl3mg"/><path class="blzwzs-bz"/><path class="gyi-tobvb"/><path class="ztr6a0gki"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:collation-outline-bold" {...props}></Icon>
<style>
:global(.blzwzs-bz) {
  d: path("M2 18h8");
}

:global(.f-x5yl3mg) {
  d: path("M2 12h11");
}

:global(.gyi-tobvb) {
  d: path("M20 5v14");
}

:global(.jtrmczbpr) {
  d: path("M2 6h14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.ztr6a0gki) {
  d: path("m17 16 3 3 2 -2");
}

</style>
