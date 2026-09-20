<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krct6gfoo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:arrow-left" {...props}></Icon>
<style>
:global(.krct6gfoo) {
  fill: currentColor;
  d: path("m14 17l-5-5l5-5z");
}

</style>
