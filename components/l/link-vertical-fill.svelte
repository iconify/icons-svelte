<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8dfhgbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:link-vertical-fill" {...props}></Icon>
<style>
:global(.i8dfhgbvx) {
  fill: currentColor;
  d: path("M7 9V7a5 5 0 0 1 10 0v2a1 1 0 0 1-2 0V7a3 3 0 1 0-6 0v2a1 1 0 0 1-2 0m6-1v8a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0m-4 7v2a3 3 0 1 0 6 0v-2a1 1 0 0 1 2 0v2a5 5 0 0 1-10 0v-2a1 1 0 0 1 2 0");
}

</style>
