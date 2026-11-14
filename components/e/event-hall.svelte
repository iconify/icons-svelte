<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ar6zorq_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:event-hall" {...props}></Icon>
<style>
:global(.ar6zorq_j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.25 5l4.051-2.132a1.5 1.5 0 0 1 1.398 0L16.75 5a1.326 1.326 0 0 1-.618 2.5H7.868A1.326 1.326 0 0 1 7.25 5M2.5 21.5V19h2v-2.5h15V19h2v2.5Zm4-14v9m5.5-9v9m5.5-9v9");
}

</style>
