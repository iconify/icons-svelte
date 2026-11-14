<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdz0w_7kz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pushpin" {...props}></Icon>
<style>
:global(.zdz0w_7kz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.243 4.222l3.535 3.535l-3.535 3.536l-1.415 6.364l-8.485-8.485l6.364-1.415Zm-5.657 9.192l-4.95 4.95");
}

</style>
