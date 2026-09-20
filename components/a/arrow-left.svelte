<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3ft3qbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrow-left" {...props}></Icon>
<style>
:global(.o3ft3qbpp) {
  fill: currentColor;
  d: path("M13.5 15.808L9.692 12L13.5 8.192z");
}

</style>
