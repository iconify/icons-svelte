<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="bct-19lvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:data-histogram-28-filled" {...props}></Icon>
<style>
:global(.bct-19lvs) {
  fill: currentColor;
  d: path("M9 25H3.75a.75.75 0 0 1-.75-.75v-9.5A2.75 2.75 0 0 1 5.75 12H9zm5.75-22a2.75 2.75 0 0 1 2.75 2.75V25h-7V5.75A2.75 2.75 0 0 1 13.25 3zm7.5 5A2.75 2.75 0 0 1 25 10.75v13.5a.75.75 0 0 1-.75.75H19V8z");
}

</style>
