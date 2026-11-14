<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yyq503bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ink-drop-cmyk" {...props}></Icon>
<style>
:global(.yyq503bai) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5s-7 7.5-7 12a7 7 0 0 0 14 0c0-4.5-7-12-7-12m0 0v19m-7-7h14");
}

</style>
