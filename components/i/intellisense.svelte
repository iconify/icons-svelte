<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="boyqfsb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:intellisense" {...props}></Icon>
<style>
:global(.boyqfsb5b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 8l-4 4l4 4m10-8l4 4l-4 4M12 5v14M10 5h4m-4 14h4");
}

</style>
