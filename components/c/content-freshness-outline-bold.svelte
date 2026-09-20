<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="abnm6smsv"/><path class="dx5s6zbrc"/><path class="gib7r1bvf"/><path class="tbr41ebiu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:content-freshness-outline-bold" {...props}></Icon>
<style>
:global(.abnm6smsv) {
  d: path("M13 3H6v18h12V8");
}

:global(.dx5s6zbrc) {
  d: path("M8 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.gib7r1bvf) {
  d: path("M12 9.5V12");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tbr41ebiu) {
  d: path("M12 12h2.5");
}

</style>
