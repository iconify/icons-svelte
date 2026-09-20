<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="a95e07reb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-2-dashes-solid-28-regular" {...props}></Icon>
<style>
:global(.a95e07reb) {
  fill: currentColor;
  d: path("M2.75 9a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5zm9 0a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5zm9 0a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5zm-18 8a.75.75 0 0 0 0 1.5h22.5a.75.75 0 0 0 0-1.5z");
}

</style>
