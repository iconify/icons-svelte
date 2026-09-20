<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="stz6wfwcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:navigation-28-regular" {...props}></Icon>
<style>
:global(.stz6wfwcf) {
  fill: currentColor;
  d: path("M2 5.75A.75.75 0 0 1 2.75 5h22.5a.75.75 0 0 1 0 1.5H2.75A.75.75 0 0 1 2 5.75m0 16a.75.75 0 0 1 .75-.75h22.5a.75.75 0 0 1 0 1.5H2.75a.75.75 0 0 1-.75-.75M2.75 13a.75.75 0 0 0 0 1.5h22.5a.75.75 0 0 0 0-1.5z");
}

</style>
