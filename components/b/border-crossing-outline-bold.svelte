<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q3srlnbfr"/><path class="mxzk029nb"/><path class="c438ceftc"/><path class="n96aj2bbi"/><path class="zpl29uvhf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:border-crossing-outline-bold" {...props}></Icon>
<style>
:global(.c438ceftc) {
  d: path("M12 17v5");
}

:global(.mxzk029nb) {
  d: path("M12 10v4");
}

:global(.n96aj2bbi) {
  d: path("M4 12h15");
}

:global(.q3srlnbfr) {
  d: path("M12 2v5");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.zpl29uvhf) {
  d: path("m16 9 3 3 -3 3");
}

</style>
