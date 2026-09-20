<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ytqok-bxz"/><path class="gorvssbqo"/><path class="e6cqo_biq"/><path class="kliut9bht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:greedy-decode-outline-regular" {...props}></Icon>
<style>
:global(.e6cqo_biq) {
  d: path("m6 12 5 -5");
}

:global(.gorvssbqo) {
  d: path("M17.5 9.5 20 12l-2.5 2.5");
}

:global(.kliut9bht) {
  d: path("m10 12 5 5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ytqok-bxz) {
  d: path("M2 12h15.5");
}

</style>
