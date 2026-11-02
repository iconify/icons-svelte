<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnitsqihh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:play-pause-round" {...props}></Icon>
<style>
:global(.tnitsqihh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m6.11 6.336l6 4a2 2 0 0 1 0 3.328l-6 4C4.78 18.55 3 17.597 3 16V8c0-1.597 1.78-2.55 3.11-1.664M17 6v12m4-12v12");
}

</style>
