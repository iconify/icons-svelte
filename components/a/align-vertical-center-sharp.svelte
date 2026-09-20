<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pag7pgb4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:align-vertical-center-sharp" {...props}></Icon>
<style>
:global(.pag7pgb4j) {
  fill: currentColor;
  d: path("M7 21v-8H2v-2h5V3h3v8h4V6h3v5h5v2h-5v5h-3v-5h-4v8z");
}

</style>
