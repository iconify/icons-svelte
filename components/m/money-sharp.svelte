<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycdq-ob8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:money-sharp" {...props}></Icon>
<style>
:global(.ycdq-ob8t) {
  fill: currentColor;
  d: path("M14 16h5V8h-5zm2-2v-4h1v4zm-8 2h5V8H8zm2-2v-4h1v4zm-5 2h2V8H5zm-3 4V4h20v16z");
}

</style>
