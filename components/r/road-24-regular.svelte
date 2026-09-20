<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r5mxzubru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:road-24-regular" {...props}></Icon>
<style>
:global(.r5mxzubru) {
  fill: currentColor;
  d: path("M5.5 2.75a.75.75 0 0 0-1.5 0v18.5a.75.75 0 0 0 1.5 0zm14.5 0a.75.75 0 0 0-1.5 0v18.5a.75.75 0 0 0 1.5 0zm-7.25 0a.75.75 0 0 0-1.5 0v3.5a.75.75 0 0 0 1.5 0zm-1.5 11a.75.75 0 0 0 1.5 0v-3.5a.75.75 0 0 0-1.5 0zm0 4a.75.75 0 0 1 1.5 0v3.5a.75.75 0 0 1-1.5 0z");
}

</style>
