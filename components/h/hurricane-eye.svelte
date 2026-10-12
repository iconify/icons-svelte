<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rd6dt9v-d"/><path class="shslhfb5e"/><circle class="h_tsn8bxt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hurricane-eye" {...props}></Icon>
<style>
:global(.h_tsn8bxt) {
  cx: 12px;
  cy: 12px;
  r: 2px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rd6dt9v-d) {
  d: path("M12 16.5a4.5 4.5 0 0 1 0-9c4.5 0 9-1.5 9-4.5");
}

:global(.shslhfb5e) {
  d: path("M12 7.5a4.5 4.5 0 0 1 0 9c-4.5 0-9 1.5-9 4.5");
}

</style>
