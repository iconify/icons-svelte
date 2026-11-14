<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku6mp8iwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:earth-ground" {...props}></Icon>
<style>
:global(.ku6mp8iwg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3v8m-7 0h14M8 15h8m-5.5 4h3");
}

</style>
