<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_p2yegdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:move" {...props}></Icon>
<style>
:global(.f_p2yegdv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19M2.5 12h19M9.25 5.25L12 2.5l2.75 2.75m-5.5 13.5L12 21.5l2.75-2.75m-9.5-9.5L2.5 12l2.75 2.75m13.5-5.5L21.5 12l-2.75 2.75");
}

</style>
