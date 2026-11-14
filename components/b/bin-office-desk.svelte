<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mth786axa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bin-office-desk" {...props}></Icon>
<style>
:global(.mth786axa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 13h19m-18 0v6.5m17-6.5v6.5M12.75 13L11.5 4.5H19L17.75 13");
}

</style>
