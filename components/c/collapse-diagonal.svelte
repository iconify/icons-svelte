<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfh_-er_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:collapse-diagonal" {...props}></Icon>
<style>
:global(.hfh_-er_f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.5 6.5l11 11M15 5v4h4M5 15h4v4");
}

</style>
