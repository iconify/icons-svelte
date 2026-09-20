<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjf5n1bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:barcode-sharp" {...props}></Icon>
<style>
:global(.vjf5n1bbw) {
  fill: currentColor;
  d: path("M1 19V5h2v14zm3 0V5h2v14zm3 0V5h1v14zm3 0V5h2v14zm3 0V5h3v14zm4 0V5h1v14zm3 0V5h3v14z");
}

</style>
