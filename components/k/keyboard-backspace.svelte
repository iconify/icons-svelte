<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrka0qbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:keyboard-backspace" {...props}></Icon>
<style>
:global(.xrka0qbfz) {
  fill: currentColor;
  d: path("m9 18l-6-6l6-6l1.4 1.4L6.8 11H21v2H6.8l3.6 3.6z");
}

</style>
