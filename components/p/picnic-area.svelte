<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ady373blu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:picnic-area" {...props}></Icon>
<style>
:global(.ady373blu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6h16M2.5 12.5h19M8.5 6L5 19M15.5 6L19 19");
}

</style>
