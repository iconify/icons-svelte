<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evdu13bpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:plus-minus" {...props}></Icon>
<style>
:global(.evdu13bpy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4.5v9M7.5 9h9m-9 10.5h9");
}

</style>
