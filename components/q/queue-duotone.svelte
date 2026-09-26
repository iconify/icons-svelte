<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jsp63q5wp"/><path class="v_lbhubrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:queue-duotone" {...props}></Icon>
<style>
:global(.jsp63q5wp) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 3L20 3C21.65685 3 23 4.34315 23 6L23 10C23 11.65685 21.65685 13 20 13L4 13C2.34315 13 1 11.65685 1 10L1 6C1 4.34315 2.34315 3 4 3Z");
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v_lbhubrs) {
  d: path("M2 16L22 16M2 20L17 20");
}

</style>
