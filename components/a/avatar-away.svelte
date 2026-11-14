<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltjoooqsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:avatar-away" {...props}></Icon>
<style>
:global(.ltjoooqsy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.072 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.718 0 1.407.064 2.057.186M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm13.25 7.5a3.75 3.75 0 1 0 1.5 5.25a3.75 3.75 0 0 1-1.5-5.25Z");
}

</style>
