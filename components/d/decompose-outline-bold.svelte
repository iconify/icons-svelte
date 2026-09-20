<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xhii43btc"/><path class="ewz7d-bxg"/><path class="z8g2jgblp"/><path class="x-fkne0xd"/><path class="dvq1jva5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:decompose-outline-bold" {...props}></Icon>
<style>
:global(.dvq1jva5q) {
  d: path("M19 12v7");
}

:global(.ewz7d-bxg) {
  d: path("M12 9v10");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x-fkne0xd) {
  d: path("M5 12v7");
}

:global(.xhii43btc) {
  d: path("M8 4a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.z8g2jgblp) {
  d: path("M5 12h14");
}

</style>
