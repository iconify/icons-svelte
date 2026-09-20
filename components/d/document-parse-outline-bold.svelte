<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="h4mbgmbqx"/><path class="bwrecrsdv"/><path class="dm6j51bgi"/><path class="v04-rubun"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:document-parse-outline-bold" {...props}></Icon>
<style>
:global(.bwrecrsdv) {
  d: path("M15 14h4");
}

:global(.dm6j51bgi) {
  d: path("m16 11 3 3 -3 3");
}

:global(.h4mbgmbqx) {
  d: path("M12 2H5v16h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.v04-rubun) {
  d: path("M14 4a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

</style>
