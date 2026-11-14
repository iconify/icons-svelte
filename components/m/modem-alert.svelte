<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zx023ot1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:modem-alert" {...props}></Icon>
<style>
:global(.zx023ot1q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.2 18H2.5v-8h17v1.7M6 10l1.5-5.5M15 10l1.5-5.5M6.5 14h.01M10 14h.01m7.99.5V18m0 3h.01");
}

</style>
