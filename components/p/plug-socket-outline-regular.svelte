<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nzpsuduik"/><path class="od2b1pbqk"/><path class="zot4lob1g"/><path class="zm2dyvb-o"/><path class="s17p06b6l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:plug-socket-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nzpsuduik) {
  d: path("M3 5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

:global(.od2b1pbqk) {
  d: path("M8 8v4");
}

:global(.s17p06b6l) {
  d: path("M12 16v-3");
}

:global(.zm2dyvb-o) {
  d: path("M9 16h6");
}

:global(.zot4lob1g) {
  d: path("M16 8v4");
}

</style>
