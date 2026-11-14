<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="larqn4bnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:fiber-terminal-off" {...props}></Icon>
<style>
:global(.larqn4bnk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 4.1V3h13v13h-1.1m-7.8 0H8v-4.1m-5.5.1H8m-5.5 3H8M3.5 3.5l17 17");
}

</style>
