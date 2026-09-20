<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="n28no-oxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-flow-diagonal-up-right-28-filled" {...props}></Icon>
<style>
:global(.n28no-oxa) {
  fill: currentColor;
  d: path("M22.5 13.25a.75.75 0 0 0 1.5 0v-8.5a.75.75 0 0 0-.75-.75h-8.5a.75.75 0 0 0 0 1.5h6.69L11 15.939a4.5 4.5 0 1 0 1.019 1.103L22.5 6.56z");
}

</style>
