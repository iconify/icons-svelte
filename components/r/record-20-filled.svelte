<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="si0ttcbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:record-20-filled" {...props}></Icon>
<style>
:global(.si0ttcbyj) {
  fill: currentColor;
  d: path("M2 10a8 8 0 1 1 16 0a8 8 0 0 1-16 0m8 4.5a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9");
}

</style>
