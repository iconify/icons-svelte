<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b9nk__b0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:analytics-funnel" {...props}></Icon>
<style>
:global(.b9nk__b0x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 4h15l-5.25 7.25V17l-3.5 2v-7.75ZM16 21.5v-3m2.75 3v-5.75m2.75 5.75v-8");
}

</style>
