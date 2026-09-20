<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cw5tdtbgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:pencil-simple-fill" {...props}></Icon>
<style>
:global(.cw5tdtbgw) {
  fill: currentColor;
  d: path("m227.31 73.37l-44.68-44.69a16 16 0 0 0-22.63 0L36.69 152A15.86 15.86 0 0 0 32 163.31V208a16 16 0 0 0 16 16h44.69a15.86 15.86 0 0 0 11.31-4.69L227.31 96a16 16 0 0 0 0-22.63M192 108.68L147.31 64l24-24L216 84.68Z");
}

</style>
