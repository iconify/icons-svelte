<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwa4a0b9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:align-justify-flex-start" {...props}></Icon>
<style>
:global(.fwa4a0b9p) {
  fill: currentColor;
  d: path("M3 21V3h1v18zm10.5-4.5v-9h2v9zm-6 0v-9h2v9z");
}

</style>
