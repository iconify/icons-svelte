<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jh4oyrbou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:direction-signpost" {...props}></Icon>
<style>
:global(.jh4oyrbou) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19M12 4h6l2.5 2.5L18 9h-6m0 2.5H6L3.5 14L6 16.5h6");
}

</style>
