<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-ef35b5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:arrow-shape-up-stack" {...props}></Icon>
<style>
:global(.d-ef35b5l) {
  fill: currentColor;
  d: path("M9.462 19v-2.98H5l7-7.5l7 7.5h-4.462V19zM5 11.27l7-7.5l7 7.5h-1.367L12 5.25l-5.633 6.02z");
}

</style>
