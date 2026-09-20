<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y92rdcc_s"/><path class="h7bcztycq"/><path class="zdy8cdcdt"/><path class="gnvc2jbpq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:indoor-plant-outline-bold" {...props}></Icon>
<style>
:global(.gnvc2jbpq) {
  d: path("M12 10c3 0 5 -2 5 -5 -3 0 -5 2 -5 5");
}

:global(.h7bcztycq) {
  d: path("M12 8v8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.y92rdcc_s) {
  d: path("M9 16v5h6v-5Z");
}

:global(.zdy8cdcdt) {
  d: path("M12 12c-3 0 -5 -2 -5 -5 3 0 5 2 5 5");
}

</style>
