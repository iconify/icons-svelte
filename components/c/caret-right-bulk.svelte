<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aib9ci-xo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:caret-right-bulk" {...props}></Icon>
<style>
:global(.aib9ci-xo) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m10.707 7.293l4 4a1 1 0 0 1 0 1.414l-4 4A1 1 0 0 1 9 16V8a1.002 1.002 0 0 1 1.707-.707");
}

</style>
