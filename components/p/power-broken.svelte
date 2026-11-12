<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ny50c9bxo"/><path class="drwdmqc5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:power-broken" {...props}></Icon>
<style>
:global(.drwdmqc5u) {
  d: path("M8.5 3.70605C5.26806 5.07157 3 8.27099 3 12.0001C3 14.3052 3.86656 16.4079 5.29169 18.0002M15.5 3.70605C18.7319 5.07157 21 8.27099 21 12.0001C21 16.9707 16.9706 21.0001 12 21.0001C10.9481 21.0001 9.93834 20.8197 9 20.488");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ny50c9bxo) {
  d: path("M12 2V6");
}

</style>
