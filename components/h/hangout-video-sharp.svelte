<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea69yzzpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:hangout-video-sharp" {...props}></Icon>
<style>
:global(.ea69yzzpy) {
  fill: currentColor;
  d: path("M6 16h8v-3.2l4 3.2V8l-4 3.2V8H6zm-4 4V4h20v16z");
}

</style>
