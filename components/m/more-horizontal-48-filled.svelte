<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ie8olfbyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:more-horizontal-48-filled" {...props}></Icon>
<style>
:global(.ie8olfbyc) {
  fill: currentColor;
  d: path("M16 24a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0m11.5 0a3.5 3.5 0 1 1-7 0a3.5 3.5 0 0 1 7 0m8 3.5a3.5 3.5 0 1 0 0-7a3.5 3.5 0 0 0 0 7");
}

</style>
