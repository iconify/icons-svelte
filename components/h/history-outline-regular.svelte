<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kv86m5bsi"/><path class="pfpu_3ppl"/><path class="dm5ccobgo"/><path class="mcj52c2nx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:history-outline-regular" {...props}></Icon>
<style>
:global(.dm5ccobgo) {
  d: path("M12 12h4");
}

:global(.kv86m5bsi) {
  d: path("M3 4v5h5");
}

:global(.mcj52c2nx) {
  d: path("M12 3a9 9 0 1 1 -9 9");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pfpu_3ppl) {
  d: path("M12 8v4");
}

</style>
