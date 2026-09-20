<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="ig6186buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:data-bar-vertical-28-filled" {...props}></Icon>
<style>
:global(.ig6186buq) {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 1 3 3v16a3 3 0 1 1-6 0V6a3 3 0 0 1 3-3m8 5a3 3 0 0 1 3 3v11a3 3 0 1 1-6 0V11a3 3 0 0 1 3-3m8 5a3 3 0 0 1 3 3v6a3 3 0 1 1-6 0v-6a3 3 0 0 1 3-3");
}

</style>
