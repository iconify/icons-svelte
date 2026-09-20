<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lbz2yq5no"/><path class="el0n_ccnv"/><path class="l517yxbln"/><path class="n4e83dijt"/><path class="g6ulbfs0a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:audio-gen-outline-regular" {...props}></Icon>
<style>
:global(.el0n_ccnv) {
  d: path("M8 5v14");
}

:global(.g6ulbfs0a) {
  d: path("M15 11h6");
}

:global(.l517yxbln) {
  d: path("M12 9v6");
}

:global(.lbz2yq5no) {
  d: path("M4 9v6");
}

:global(.n4e83dijt) {
  d: path("M18 8v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
