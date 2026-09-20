<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4e-jwdzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:first-page-outline" {...props}></Icon>
<style>
:global(.m4e-jwdzh) {
  fill: currentColor;
  d: path("M6.5 17.5v-11h1v11zm10.5-.192L11.692 12L17 6.692l.708.708l-4.6 4.6l4.6 4.6z");
}

</style>
