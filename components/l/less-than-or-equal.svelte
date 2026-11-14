<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkb011n6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:less-than-or-equal" {...props}></Icon>
<style>
:global(.gkb011n6s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 3.5L7 9l10 5.5m-10 5h10");
}

</style>
