<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yj3b4r-dx"/><path class="ccmgq7b4f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:piste-expert" {...props}></Icon>
<style>
:global(.ccmgq7b4f) {
  d: path("M12 11v10.5m-3 0h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yj3b4r-dx) {
  fill: currentColor;
  d: path("m3.561 6.939l1.878-1.878a1.5 1.5 0 0 1 2.122 0l1.878 1.878a1.5 1.5 0 0 1 0 2.122l-1.878 1.878a1.5 1.5 0 0 1-2.122 0L3.561 9.061a1.5 1.5 0 0 1 0-2.122m11 0l1.878-1.878a1.5 1.5 0 0 1 2.122 0l1.878 1.878a1.5 1.5 0 0 1 0 2.122l-1.878 1.878a1.5 1.5 0 0 1-2.122 0l-1.878-1.878a1.5 1.5 0 0 1 0-2.122");
}

</style>
