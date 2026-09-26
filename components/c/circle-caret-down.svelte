<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tx_ah59as"/><path class="khm6ujbwc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:circle-caret-down" {...props}></Icon>
<style>
:global(.khm6ujbwc) {
  d: path("M11.5301 16.7267L7.06842 8.78926C6.86937 8.43516 7.12844 8 7.5383 8H16.4617C16.8716 8 17.1306 8.43516 16.9316 8.78926L12.4699 16.7267C12.2651 17.0911 11.7349 17.0911 11.5301 16.7267Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tx_ah59as) {
  d: path("M12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2Z");
}

</style>
