<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ouxbkjcpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-flow-diagonal-up-right-32-filled" {...props}></Icon>
<style>
:global(.ouxbkjcpj) {
  fill: currentColor;
  d: path("M26.707 6.707a1 1 0 0 0-1.414-1.414L11.618 18.968a5.5 5.5 0 1 0 1.414 1.414z");
}

</style>
