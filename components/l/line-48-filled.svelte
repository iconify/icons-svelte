<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j9lo0vple"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-48-filled" {...props}></Icon>
<style>
:global(.j9lo0vple) {
  fill: currentColor;
  d: path("M43.56 4.44a1.5 1.5 0 0 1 0 2.12l-37 37a1.5 1.5 0 0 1-2.12-2.12l37-37a1.5 1.5 0 0 1 2.12 0");
}

</style>
