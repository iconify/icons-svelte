<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="if8e760xe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:play-28-filled" {...props}></Icon>
<style>
:global(.if8e760xe) {
  fill: currentColor;
  d: path("M10.138 3.382C8.304 2.31 6 3.632 6 5.756v16.489c0 2.123 2.304 3.445 4.138 2.374l14.697-8.59c1.552-.907 1.552-3.15 0-4.057z");
}

</style>
