<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e1otdgb2g"/><path class="ngysh-w9y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:audio-lines-low-two-tone" {...props}></Icon>
<style>
:global(.e1otdgb2g) {
  stroke-opacity: 0.4;
  d: path("M8 10V14M16 11V13");
}

:global(.ngysh-w9y) {
  d: path("M4 11V13M12 8V16M20 10V14");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
