<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e28pixblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:book-stand" {...props}></Icon>
<style>
:global(.e28pixblc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.5c-2.5-2-6-2.5-9-2v9c3-.5 6.5 0 9 2c2.5-2 6-2.5 9-2v-9c-3-.5-6.5 0-9 2m0 0v15m-4.5 0h9");
}

</style>
