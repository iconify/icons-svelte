<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cle-vebav"/><path class="s3781acdv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:clan-banner" {...props}></Icon>
<style>
:global(.cle-vebav) {
  d: path("M5 3.25h14m-12.5 0v11.5h11V3.25M12 14.75v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s3781acdv) {
  d: path("M9.25 8.25L12 11l2.75-2.75");
}

</style>
