<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q_wdh4bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:maximize" {...props}></Icon>
<style>
:global(.q_wdh4bfz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13 11l6.5-6.5m-6 0h6v6M11 13l-6.5 6.5m6 0h-6v-6");
}

</style>
