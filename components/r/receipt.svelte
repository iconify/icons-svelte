<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuhkklbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:receipt" {...props}></Icon>
<style>
:global(.uuhkklbel) {
  fill: currentColor;
  d: path("M3 22V2l1.5 1.5L6 2l1.5 1.5L9 2l1.5 1.5L12 2l1.5 1.5L15 2l1.5 1.5L18 2l1.5 1.5L21 2v20l-1.5-1.5L18 22l-1.5-1.5L15 22l-1.5-1.5L12 22l-1.5-1.5L9 22l-1.5-1.5L6 22l-1.5-1.5zm3-5h12v-2H6zm0-4h12v-2H6zm0-4h12V7H6z");
}

</style>
