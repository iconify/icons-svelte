<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="n_gwv4tcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:cell-signal-medium-bold" {...props}></Icon>
<style>
:global(.n_gwv4tcc) {
  fill: currentColor;
  d: path("M132 112v88a12 12 0 0 1-24 0v-88a12 12 0 0 1 24 0m-52 28a12 12 0 0 0-12 12v48a12 12 0 0 0 24 0v-48a12 12 0 0 0-12-12m-40 40a12 12 0 0 0-12 12v8a12 12 0 0 0 24 0v-8a12 12 0 0 0-12-12");
}

</style>
