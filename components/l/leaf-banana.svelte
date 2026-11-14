<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qh37k9kdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:leaf-banana" {...props}></Icon>
<style>
:global(.qh37k9kdd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5C7 18 6.5 12 7 9l2.25.5L7.5 7Q9 4 12 2.5Q15 4 16.5 7l-1.75 2.5L17 9c.5 3 0 9-5 12.5M12 6v15.5");
}

</style>
