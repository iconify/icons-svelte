<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ygnv14b_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:flip-horizontal-20-filled" {...props}></Icon>
<style>
:global(.ygnv14b_a) {
  fill: currentColor;
  d: path("M17.878 15.66a.75.75 0 0 1-.628.34h-5.5a.75.75 0 0 1-.75-.75V2.75a.75.75 0 0 1 1.437-.302l5.5 12.5a.75.75 0 0 1-.059.712M12.5 6.317V14.5h3.6zM2.5 16a.5.5 0 0 1-.454-.71l6-13A.5.5 0 0 1 9 2.5v13a.5.5 0 0 1-.5.5z");
}

</style>
