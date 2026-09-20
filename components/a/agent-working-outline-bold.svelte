<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nrlkc9bnf"/><path class="w28ybhbjm"/><path class="h7bcztycq"/><path class="h0r-78wsa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-working-outline-bold" {...props}></Icon>
<style>
:global(.h0r-78wsa) {
  d: path("M17 10v4");
}

:global(.h7bcztycq) {
  d: path("M12 8v8");
}

:global(.nrlkc9bnf) {
  d: path("M4 12a8 8 0 1 0 16 0 8 8 0 1 0 -16 0");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.w28ybhbjm) {
  d: path("M7 10v4");
}

</style>
