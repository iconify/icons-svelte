<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ge7jckuff"/><path class="etx6lfb3j"/><path class="xw-kcgifr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mcp-stdio-outline-bold" {...props}></Icon>
<style>
:global(.etx6lfb3j) {
  d: path("M2 9h4");
}

:global(.ge7jckuff) {
  d: path("M12 4h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H9a3 3 0 0 1 -3 -3V7l3 -3Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xw-kcgifr) {
  d: path("M18 15h4");
}

</style>
