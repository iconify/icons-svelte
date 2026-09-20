<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xyj-l9cjp"/><path class="y-a5g9b6x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:market-closed-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xyj-l9cjp) {
  d: path("M3 18h18");
}

:global(.y-a5g9b6x) {
  d: path("M12 3a6.5 6.5 0 1 0 6.5 9.5A5.5 5.5 0 0 1 12 3");
}

</style>
