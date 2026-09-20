<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="vpcy3eezg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:divider-tall-20-filled" {...props}></Icon>
<style>
:global(.vpcy3eezg) {
  fill: currentColor;
  d: path("M9.75 1a.75.75 0 0 1 .75.75v16.5a.75.75 0 0 1-1.5 0V1.75A.75.75 0 0 1 9.75 1");
}

</style>
